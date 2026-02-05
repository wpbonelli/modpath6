# MODPATH Version 6

[![mp6 checks](https://github.com/MODFLOW-ORG/modpath6/actions/workflows/ci.yml/badge.svg)](https://github.com/MODFLOW-ORG/modpath6/actions/workflows/ci.yml)

## Overview of MODPATH 6

MODPATH 6 is a particle-tracking post-processing model that computes three-dimensional flow paths using output from groundwater flow simulations based on MODFLOW, the U.S. Geological Survey (USGS) finite-difference groundwater flow model. The program uses a semianalytical particle-tracking scheme that allows an analytical expression of a particle's flow path to be obtained within each finite-difference grid cell. A particle's path is computed by tracking the particle from one cell to the next until it reaches a boundary, an internal sink/source, or satisfies another termination criterion. Data input to MODPATH consists of a combination of MODFLOW input data files, MODFLOW head and flow output files, and other input files specific to MODPATH. Output from MODPATH consists of several output files, including a number of particle coordinate output files intended to serve as input data for other programs that process, analyze, and display the results in various ways.

## How to Cite MODPATH 6

Pollock, D.W., 2012, User guide for MODPATH Version 6--A particle-tracking model for MODFLOW: U.S. Geological Survey Techniques and Methods, book 6, chap. A41, 58 p., https://doi.org/10.3133/tm6A41
