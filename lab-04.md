Lab 04 - La Quinta is Spanish for next to Denny’s, Pt. 1
================
Lindley
02/15/2021

### Load packages and data

``` r
library(tidyverse) 
```

``` r
states <- read_csv("data/states.csv")
load("G:\\My Drive\\DataScience\\Lab_04\\data\\dennys.rda")
load("G:\\My Drive\\DataScience\\Lab_04\\data\\laquinta.rda")
```

### Exercise 1

``` r
glimpse(dennys)
```

    ## Observations: 1,643
    ## Variables: 6
    ## $ address   <chr> "2900 Denali", "3850 Debarr Road", "1929 Airport Way", "2...
    ## $ city      <chr> "Anchorage", "Anchorage", "Fairbanks", "Auburn", "Birming...
    ## $ state     <chr> "AK", "AK", "AK", "AL", "AL", "AL", "AL", "AL", "AL", "AL...
    ## $ zip       <chr> "99503", "99508", "99701", "36849", "35207", "35294", "35...
    ## $ longitude <dbl> -149.8767, -149.8090, -147.7600, -85.4681, -86.8317, -86....
    ## $ latitude  <dbl> 61.1953, 61.2097, 64.8366, 32.6033, 33.5615, 33.5007, 34....

There are 1,643 observation and 6 columns. Each observation represents a
particular dennys.

### Exercise 2

``` r
glimpse(laquinta)
```

    ## Observations: 909
    ## Variables: 6
    ## $ address   <chr> "793 W. Bel Air Avenue", "3018 CatClaw Dr", "3501 West La...
    ## $ city      <chr> "\nAberdeen", "\nAbilene", "\nAbilene", "\nAcworth", "\nA...
    ## $ state     <chr> "MD", "TX", "TX", "GA", "OK", "TX", "AG", "TX", "NM", "NM...
    ## $ zip       <chr> "21001", "79606", "79601", "30102", "74820", "75254", "20...
    ## $ longitude <dbl> -76.18846, -99.77877, -99.72269, -84.65609, -96.63652, -9...
    ## $ latitude  <dbl> 39.52322, 32.41349, 32.49136, 34.08204, 34.78180, 32.9516...

There are 909 observations and 6 variables. Each observation is a
particular la quinta.

### Exercise 3

There are no dennys outside the US. There are la quintas outside the US
(Mexico, New Zealand, Honduras, Turkey, Chile, Columbia, and Canada).

### Exercise 4

…

### Exercise 5

…

### Exercise 6

…

Add exercise headings as needed.
