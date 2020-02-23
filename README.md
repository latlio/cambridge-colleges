# Visiting All 31 Cambridge Colleges

The motivation for this project was to find the most efficient path to visit all 31 colleges in Cambridge for a YouTube video. I treated this like a Traveling Salesman Problem and used simulated annealing to find the most shortest tour for various clusters of Cambridge colleges (center, river, hill). I implement the naive way of using iterative swaps between adjacent points to determine shortest path (i.e. if a swap produces a shorter path, keep the new path, otherwise, randomize and repeat). Assumptions: straight line paths, coordinates represent college entrances, and Euclidean distance.

## Prerequisites
You need a Google API key enabled for the Distance Matrix, Geocoding, and Maps Static API. These are the following R packages I used:

```
install.packages("tidyverse")
install.packages("rjson")
install.packages("readxl")
install.packages("ggmap")
install.packages("fs")
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

