# Code used to produce results for my dissertation titled Biologically Inspired Spiking Neural Networks for Signal Processing and Classification

Includes a copy of ...
### Liquid State Machine (LSM)

The Liquid State Machine (LSM) ([Maass et. al. 2002][1]) is a computational model
which uses the high-dimensional, complex dynamics of recurrent neural circuits to
conduct memory-dependent readout operations on continuous input streams.

[1]:http://dx.doi.org/10.1162/089976602760407955

This package provides a convenience wrapper for network construction, as well as typical
operations on the reservoir.

##### Usage

After cloning this repository locally, run `pip install .` in the working copy. Requires a working installation of the [NEST simulator](http://www.nest-initiative.org).
