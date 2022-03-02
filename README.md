# Data Acquisition and Processing Systems (DaPS) (ELEC0136)

Welcome to the final assignment of the _Data Acquisition and Processing Systems_ (DaPS) course ELEC0136 at UCL.

The objective of this assignment is to simulate a real-life data-science situation that can be
approached using the process described in class: i) finding a source of data, ii) acquiring and
storing it iii) cleaning and preprocessing it, iv) extracting meaningful visualisations, v) building a
model for inference. You are also free to use any additional methods you find are well suited for
the problem.

## Overview

Financial data from Yahoo! Finance API `yfinance` __or__ from local csv manually sourced from webpage, 'trend' data from Google Trends API __or__ using `pytrends` API.

Apache Arrow `feather` binary file format used for local *hot* storage of timeseries data.

Multiple statistical tests and visualizations performed pre-model.

LSTMs forecast model for both:

- only finanical data
- financial + google trends data

