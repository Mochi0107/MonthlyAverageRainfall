This repository contains an analysis of average monthly rainfall in Oxford and Melbourne, using data obtained between 1855-2015.

To run the analysis first run:
  
```
Rscript average-rainfall/src/combine-data.R
```
to receive `average-rainfall.csv`.

Then run: 

```
Rscript make-plot/src/make-plot.R 
```
to receive `result.png`.

The input data is in `data` and the results are in `out` in the respective directories. 
