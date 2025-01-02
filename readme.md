# Data Quality Assessment

This sample code provides a simple introduction to using. the [Great Expectations](https://greatexpectations.io) library (version 1.3.0) in python. This library is suitable for production scale data assessment, but does have a steep learning curve.

## Expectations

To assess data quality, expectations for quality need to be defined and agreed between data quality analysts and subject matter experts. 

With expectations set, they can be expressed as rules to measure data against. For example, a table needs to contain certain columns, and of the right type; fields values may need to be unique, or may need to conform to a given domain of values. 

Whatever the expectations, they will require checking on a regular basis to ensure data quality is being maintained, or to identify where problems might be occurring. 

It would also be really handy to have some sort of documentation generated that we could keep along with our data to demonstrate what was assessed, how the data performed, and whether any additional rules might be needed.

The *great_expectations* library provides tools to assist.

To get started, and in a new python environment, use pip to install:

``` shell
pip install great-expectations
```

To verify, using python in your cloned environment, run:

``` python
import great_expectations as gx
print(gx.__version__)
```
This returns the current version of great-expectations - 1.3.0 (as at 1 Janaury 2025)