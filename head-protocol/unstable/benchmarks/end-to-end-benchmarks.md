--- 
sidebar_label: 'End-to-end benchmarks' 
sidebar_position: 4 
--- 

# End-to-end benchmark results 

This page is intended to collect the latest end-to-end benchmark  results produced by Hydra's continuous integration (CI) system from  the latest `master` code.

:::caution

Please note that these results are approximate  as they are currently produced from limited cloud VMs and not controlled hardware.  Rather than focusing on the absolute results,   the emphasis should be on relative results,  such as how the timings for a scenario evolve as the code changes.

:::

_Generated at_  2026-06-18 05:09:09.121399342 UTC


## Baseline Scenario



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 300 |
| _Avg. Confirmation Time (ms)_ | 519.3 |
| _P99_ | 534.0ms |
| _P95_ | 533.7ms |
| _P50_ | 522.2ms |
| _End-to-end TPS_ | 556.46 tx/s |
| _Snapshots observed_ | 4 |
| _Per-snapshot TPS P50_ | 3805.18 tx/s |
| _Per-snapshot TPS P95_ | 7224.65 tx/s |
| _Per-snapshot TPS max_ | 7575.61 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Three local nodes



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 900 |
| _Avg. Confirmation Time (ms)_ | 2808.2 |
| _P99_ | 3106.0ms |
| _P95_ | 3086.1ms |
| _P50_ | 2880.8ms |
| _End-to-end TPS_ | 288.95 tx/s |
| _Snapshots observed_ | 10 |
| _Per-snapshot TPS P50_ | 873.21 tx/s |
| _Per-snapshot TPS P95_ | 2582.39 tx/s |
| _Per-snapshot TPS max_ | 2779.91 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      
