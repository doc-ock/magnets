# Magnet Lab Report
**Written in Python 3.8 by Alex C.** 

The best way to install the jupyter notebook dependencies is to install conda and activate the provided environment using `conda env create -f environment.yml`

To utilize the environment and ensure the code runs on your computer, download miniconda from [conda.io](https://docs.conda.io/en/latest/miniconda.html).

## Data
The data was taken through Google Science Journal on iOS 14.
Each test was run for 5 seconds 5 times, and then exported to a .csv file. 
The raw files are in the directory `./magnet-data/`.

The gathered data was analyzed using matplotlib.pyplot, numpy, and scipy.stats. 

## Outputs
Check `./figs/` for .png files of the data from each of the results. 
The subdirectory `./out/` contains csv files of each dataset where the first row is the mean, the second row is the standard deviation, and the third row is the chisquared values.


## Reproducing the Outputs
In a bash shell with conda installed run:

```bash    
git clone https://github.com/doc-ock/magnets.git 
cd magnets
conda env create -f environment.yml
conda activate magnets
```

Once you are in an environment that has the required packages, open the jupyter notebook:

```sh
jupyter notebook
```