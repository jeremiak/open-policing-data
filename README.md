# open data policing exploration

## install (be in the root project folder)

0. `docker pull jeremiak/pandas-notebook`
1. `docker run -it --rm -p 8888:8888 -v $PWD:/work jeremiak/pandas-notebook`

## background

data pulled from
[standford's open policing project](https://openpolicing.stanford.edu/data/).

## ideas

* animate each stop as it occurs, like a year in traffic stops
  * each dot could be a different color representing the gender of the driver
* something to figure out which officer makes the most stops and for what
* what violations are most likely to result in a search?
