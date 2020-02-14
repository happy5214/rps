# Riesel Prime Results

This repository contains most of my results from searching for Riesel primes.

It is divided into single-*k* and multi-*k* results.

## Single-*k* results

The single-*k* results are in the root of the repository. They contain a series of *n* ranges and *n* values for all primes and twins found in those ranges, with the exception of some early data which omits already-known primes.

These results are stored in a YAML format I devised for my internal networking setup. Here is the format:

- The first two lines of each file are for the internal use of that setup and can be ignored.
- The *k*, maximum *n* tested, and minimum *n* tested follow.
- The prime *n* values are listed line-by-line. If this is an empty set of square brackets, no primes have been found in the tested ranges.
- The `results` are pairs of maximum and minimum tested *n* values corresponding to testing runs.
- The twin *n* values are listed similarly to the prime *n* values.

Selected LLR logs are available upon request, based on whether I can actually find the logs.

## Multi-*k* results

The multi-*k* results are stored in several folders. The LLR logs are in \*.log files, where available. The primes are stored in \*.txt or \*.r.txt files based on range, with the format being that of LLR (with or without headers). The twins are stored in \*.twins.txt files as *k*-*n* pairs. If a twin file is not included for a range, that means no twin primes were found.
