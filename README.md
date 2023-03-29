# log-m
Fractional Brownian motion project, LoG(M) WN23

## Working notes
- Planning to do a performance analysis on the Wood-Chan algorithm implementation and possibly FFT (random walks would be good too). Some notes:
  - Mainly just measuring execution time since I can't find a reliable way to measure instruction counts or cycles, and I don't understand which metrics to consider for memory usage.
  - Also measure wall clock time for funsies
  - got `perf` to work in CAEN but the output format is horrible and I don't feel like dealing with it. Alternative: `time`.
  - Make sure to exclude any graph generation (not just output!)
  - Ideally, plot these in a reproducible way, which means I can't be manually reformatting the perfomance tool output before plugging it into my plots.
