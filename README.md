# RecBoleExperiments
Testing on RecBole recommendation framework

## Dataset
The suitable format of datasets for RecBole should be similar to the datasets files in `.inter` format. We need to add a row which indicates the names and the format of each column.

## Configuration
For configuration, we can either have a configuration file in `yaml` format or have the configs on as a parameter dict. The essential part of configuration, when you have your own splitted datasets, is `'benchmark_filename': ['train', 'tune', 'test'],`
