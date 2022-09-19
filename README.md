# About

This repository contains a brief analysis on two datasets:


| Dataset | Description |
| --- | --- |
| [Tides](https://www.digitalocean.ie/Data/DownloadTideData) | Measures about **Tides** collected by several buoys at the Ireland Sea |
| [Waves](https://www.digitalocean.ie/Data/DownloadWaveData) | Measures about **Waves** collected by several buoys at the Ireland Sea |

# Analysis

The data were collected between 2021-09-16 00:01 and 2022-09-16 23:59.

The source code is divided between two files located in the application directory:

- required_answers.ipynb
- bonus_answers.ipynb

The final report it is located in the answers_and_deicions.pdf file. In this file there are the answers of the questions and the explanation of the decisions.

**Required Answers**

This file aims to answer these questions:

1. What is the lowest temperature of each one of the Buoys?
    1. Which usually month it occurs?
2. Where (lat/long) do we have the biggest water level?
    1. Which usually month it occurs?
3. How the Wave Lenghts correlates with Sea Temperature?
    1. It is possible to predict with accuracy the Wave Lenght, based on the Sea Temperature and the Buoy location?

**Bonus Answers**

In this file, it was builded two types of machine learning models:

- A Time Series model that can predict the sea temperature throughout the year.
- A KMeans model that group the oceans tides based on it's characteristics.

## Reproduce the analysis

To run locally, clone the repository, go to the diretory and install the requirements.

```
pip install -r requirements.txt
```

You can run each analysis separated to analyze the results.
