--- 
sidebar_label: 'Scenario benchmarks' 
sidebar_position: 5 
--- 

# Scenario benchmark results 

This page collects results from the scenario matrix: every combination  of cluster size, UTxO shape, and incremental-ops mode is exercised by  CI from the latest `master` code and reported below.

:::caution

Numbers are approximate. They come from cloud VMs rather than  controlled hardware, so the useful signal is the relative change  between cells and between commits, not the absolute throughput.

:::

_Generated at_  2026-06-18 05:19:39.115467151 UTC


## Summary across cells

TPS columns are rates (transactions per second); _Wall clock (s)_ is the measured elapsed time from the first tx submission to the last confirmation. Times are rounded to one decimal.

| Scenario | Txs | Wall clock (s) | End-to-end TPS (tx/s) | Per-snapshot p50 TPS (tx/s) | Avg conf (ms) | P95 conf (ms) |
| -- | -- | -- | -- | -- | -- | -- |
| Nodes=1, Constant, incremental ops off, fire and forget | 30 | 0.1 | 507.35 | 2067.03 | 58.3 | 58.9 |
| Nodes=1, Constant, incremental ops off, wait for tx valid | 30 | 0.2 | 175.23 | 179.82 | 5.6 | 7.1 |
| Nodes=1, Growing, incremental ops off, fire and forget | 30 | 0.1 | 431.88 | 1093.27 | 68.1 | 69.2 |
| Nodes=1, Growing, incremental ops off, wait for tx valid | 30 | 0.3 | 113.93 | 122.58 | 8.7 | 11.7 |
| Nodes=1, Mixed, incremental ops off, fire and forget | 30 | 0.1 | 469.06 | 2169.04 | 62.9 | 63.7 |
| Nodes=1, Mixed, incremental ops off, wait for tx valid | 30 | 0.2 | 136.19 | 136.92 | 7.3 | 9.7 |
| Nodes=2, Constant, incremental ops off, fire and forget | 60 | 0.2 | 341.63 | 1629.43 | 173.6 | 175.2 |
| Nodes=2, Constant, incremental ops off, wait for tx valid | 60 | 0.6 | 108.76 | 119.16 | 18.2 | 24.7 |
| Nodes=2, Growing, incremental ops off, fire and forget | 60 | 0.2 | 322.34 | 649.09 | 183.6 | 185.7 |
| Nodes=2, Growing, incremental ops off, wait for tx valid | 60 | 1.0 | 61.51 | 62.83 | 31.9 | 45.9 |
| Nodes=2, Mixed, incremental ops off, fire and forget | 60 | 0.2 | 372.02 | 1067.58 | 158.9 | 160.0 |
| Nodes=2, Mixed, incremental ops off, wait for tx valid | 60 | 0.8 | 79.54 | 81.17 | 24.8 | 36.8 |
| Nodes=3, Constant, incremental ops off, fire and forget | 90 | 0.3 | 331.41 | 1582.28 | 268.4 | 270.2 |
| Nodes=3, Constant, incremental ops off, wait for tx valid | 90 | 1.0 | 90.20 | 78.08 | 32.2 | 42.2 |
| Nodes=3, Growing, incremental ops off, fire and forget | 90 | 0.3 | 262.67 | 514.27 | 338.4 | 340.9 |
| Nodes=3, Growing, incremental ops off, wait for tx valid | 90 | 2.0 | 45.38 | 43.28 | 63.9 | 102.7 |
| Nodes=3, Mixed, incremental ops off, fire and forget | 90 | 0.3 | 307.14 | 1323.00 | 289.6 | 292.6 |
| Nodes=3, Mixed, incremental ops off, wait for tx valid | 90 | 1.4 | 63.78 | 62.51 | 46.4 | 65.0 |


## Nodes=1, Constant, incremental ops off, fire and forget



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 30 |
| _Avg. Confirmation Time (ms)_ | 58.3 |
| _P99_ | 58.9ms |
| _P95_ | 58.9ms |
| _P50_ | 58.5ms |
| _End-to-end TPS_ | 507.35 tx/s |
| _Snapshots observed_ | 2 |
| _Per-snapshot TPS P50_ | 2067.03 tx/s |
| _Per-snapshot TPS P95_ | 3910.07 tx/s |
| _Per-snapshot TPS max_ | 4073.90 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=1, Constant, incremental ops off, wait for tx valid



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 30 |
| _Avg. Confirmation Time (ms)_ | 5.6 |
| _P99_ | 7.9ms |
| _P95_ | 7.1ms |
| _P50_ | 5.5ms |
| _End-to-end TPS_ | 175.23 tx/s |
| _Snapshots observed_ | 30 |
| _Per-snapshot TPS P50_ | 179.82 tx/s |
| _Per-snapshot TPS P95_ | 195.16 tx/s |
| _Per-snapshot TPS max_ | 197.22 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=1, Growing, incremental ops off, fire and forget



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 30 |
| _Avg. Confirmation Time (ms)_ | 68.1 |
| _P99_ | 69.3ms |
| _P95_ | 69.2ms |
| _P50_ | 68.4ms |
| _End-to-end TPS_ | 431.88 tx/s |
| _Snapshots observed_ | 2 |
| _Per-snapshot TPS P50_ | 1093.27 tx/s |
| _Per-snapshot TPS P95_ | 2061.16 tx/s |
| _Per-snapshot TPS max_ | 2147.19 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=1, Growing, incremental ops off, wait for tx valid



| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 30 |
| _Avg. Confirmation Time (ms)_ | 8.7 |
| _P99_ | 17.2ms |
| _P95_ | 11.7ms |
| _P50_ | 8.0ms |
| _End-to-end TPS_ | 113.93 tx/s |
| _Snapshots observed_ | 30 |
| _Per-snapshot TPS P50_ | 122.58 tx/s |
| _Per-snapshot TPS P95_ | 165.06 tx/s |
| _Per-snapshot TPS max_ | 173.91 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=1, Mixed, incremental ops off, fire and forget

Each client first grows its UTxO set (1-in to 2-out) for half of its tx budget, then contracts it back (2-in to 1-out) for the remainder.

| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 30 |
| _Avg. Confirmation Time (ms)_ | 62.9 |
| _P99_ | 63.7ms |
| _P95_ | 63.7ms |
| _P50_ | 63.2ms |
| _End-to-end TPS_ | 469.06 tx/s |
| _Snapshots observed_ | 2 |
| _Per-snapshot TPS P50_ | 2169.04 tx/s |
| _Per-snapshot TPS P95_ | 4105.45 tx/s |
| _Per-snapshot TPS max_ | 4277.57 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=1, Mixed, incremental ops off, wait for tx valid

Each client first grows its UTxO set (1-in to 2-out) for half of its tx budget, then contracts it back (2-in to 1-out) for the remainder.

| Number of nodes |  1 | 
| -- | -- |
| _Number of txs_ | 30 |
| _Avg. Confirmation Time (ms)_ | 7.3 |
| _P99_ | 10.3ms |
| _P95_ | 9.7ms |
| _P50_ | 7.2ms |
| _End-to-end TPS_ | 136.19 tx/s |
| _Snapshots observed_ | 30 |
| _Per-snapshot TPS P50_ | 136.92 tx/s |
| _Per-snapshot TPS P95_ | 170.00 tx/s |
| _Per-snapshot TPS max_ | 185.79 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=2, Constant, incremental ops off, fire and forget



| Number of nodes |  2 | 
| -- | -- |
| _Number of txs_ | 60 |
| _Avg. Confirmation Time (ms)_ | 173.6 |
| _P99_ | 175.3ms |
| _P95_ | 175.2ms |
| _P50_ | 173.8ms |
| _End-to-end TPS_ | 341.63 tx/s |
| _Snapshots observed_ | 2 |
| _Per-snapshot TPS P50_ | 1629.43 tx/s |
| _Per-snapshot TPS P95_ | 3090.17 tx/s |
| _Per-snapshot TPS max_ | 3220.01 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=2, Constant, incremental ops off, wait for tx valid



| Number of nodes |  2 | 
| -- | -- |
| _Number of txs_ | 60 |
| _Avg. Confirmation Time (ms)_ | 18.2 |
| _P99_ | 25.6ms |
| _P95_ | 24.7ms |
| _P50_ | 17.6ms |
| _End-to-end TPS_ | 108.76 tx/s |
| _Snapshots observed_ | 60 |
| _Per-snapshot TPS P50_ | 119.16 tx/s |
| _Per-snapshot TPS P95_ | 151.21 tx/s |
| _Per-snapshot TPS max_ | 158.62 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=2, Growing, incremental ops off, fire and forget



| Number of nodes |  2 | 
| -- | -- |
| _Number of txs_ | 60 |
| _Avg. Confirmation Time (ms)_ | 183.6 |
| _P99_ | 185.7ms |
| _P95_ | 185.7ms |
| _P50_ | 184.3ms |
| _End-to-end TPS_ | 322.34 tx/s |
| _Snapshots observed_ | 2 |
| _Per-snapshot TPS P50_ | 649.09 tx/s |
| _Per-snapshot TPS P95_ | 1226.81 tx/s |
| _Per-snapshot TPS max_ | 1278.16 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=2, Growing, incremental ops off, wait for tx valid



| Number of nodes |  2 | 
| -- | -- |
| _Number of txs_ | 60 |
| _Avg. Confirmation Time (ms)_ | 31.9 |
| _P99_ | 46.7ms |
| _P95_ | 45.9ms |
| _P50_ | 31.4ms |
| _End-to-end TPS_ | 61.51 tx/s |
| _Snapshots observed_ | 60 |
| _Per-snapshot TPS P50_ | 62.83 tx/s |
| _Per-snapshot TPS P95_ | 110.27 tx/s |
| _Per-snapshot TPS max_ | 135.95 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=2, Mixed, incremental ops off, fire and forget

Each client first grows its UTxO set (1-in to 2-out) for half of its tx budget, then contracts it back (2-in to 1-out) for the remainder.

| Number of nodes |  2 | 
| -- | -- |
| _Number of txs_ | 60 |
| _Avg. Confirmation Time (ms)_ | 158.9 |
| _P99_ | 160.1ms |
| _P95_ | 160.0ms |
| _P50_ | 159.3ms |
| _End-to-end TPS_ | 372.02 tx/s |
| _Snapshots observed_ | 2 |
| _Per-snapshot TPS P50_ | 1067.58 tx/s |
| _Per-snapshot TPS P95_ | 2021.61 tx/s |
| _Per-snapshot TPS max_ | 2106.42 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=2, Mixed, incremental ops off, wait for tx valid

Each client first grows its UTxO set (1-in to 2-out) for half of its tx budget, then contracts it back (2-in to 1-out) for the remainder.

| Number of nodes |  2 | 
| -- | -- |
| _Number of txs_ | 60 |
| _Avg. Confirmation Time (ms)_ | 24.8 |
| _P99_ | 37.2ms |
| _P95_ | 36.8ms |
| _P50_ | 23.5ms |
| _End-to-end TPS_ | 79.54 tx/s |
| _Snapshots observed_ | 60 |
| _Per-snapshot TPS P50_ | 81.17 tx/s |
| _Per-snapshot TPS P95_ | 111.49 tx/s |
| _Per-snapshot TPS max_ | 124.70 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=3, Constant, incremental ops off, fire and forget



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 90 |
| _Avg. Confirmation Time (ms)_ | 268.4 |
| _P99_ | 270.3ms |
| _P95_ | 270.2ms |
| _P50_ | 269.4ms |
| _End-to-end TPS_ | 331.41 tx/s |
| _Snapshots observed_ | 2 |
| _Per-snapshot TPS P50_ | 1582.28 tx/s |
| _Per-snapshot TPS P95_ | 3002.60 tx/s |
| _Per-snapshot TPS max_ | 3128.85 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=3, Constant, incremental ops off, wait for tx valid



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 90 |
| _Avg. Confirmation Time (ms)_ | 32.2 |
| _P99_ | 52.3ms |
| _P95_ | 42.2ms |
| _P50_ | 31.9ms |
| _End-to-end TPS_ | 90.20 tx/s |
| _Snapshots observed_ | 62 |
| _Per-snapshot TPS P50_ | 78.08 tx/s |
| _Per-snapshot TPS P95_ | 172.05 tx/s |
| _Per-snapshot TPS max_ | 199.31 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=3, Growing, incremental ops off, fire and forget



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 90 |
| _Avg. Confirmation Time (ms)_ | 338.4 |
| _P99_ | 341.0ms |
| _P95_ | 340.9ms |
| _P50_ | 340.1ms |
| _End-to-end TPS_ | 262.67 tx/s |
| _Snapshots observed_ | 2 |
| _Per-snapshot TPS P50_ | 514.27 tx/s |
| _Per-snapshot TPS P95_ | 973.54 tx/s |
| _Per-snapshot TPS max_ | 1014.36 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=3, Growing, incremental ops off, wait for tx valid



| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 90 |
| _Avg. Confirmation Time (ms)_ | 63.9 |
| _P99_ | 124.9ms |
| _P95_ | 102.7ms |
| _P50_ | 61.9ms |
| _End-to-end TPS_ | 45.38 tx/s |
| _Snapshots observed_ | 62 |
| _Per-snapshot TPS P50_ | 43.28 tx/s |
| _Per-snapshot TPS P95_ | 113.15 tx/s |
| _Per-snapshot TPS max_ | 126.36 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=3, Mixed, incremental ops off, fire and forget

Each client first grows its UTxO set (1-in to 2-out) for half of its tx budget, then contracts it back (2-in to 1-out) for the remainder.

| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 90 |
| _Avg. Confirmation Time (ms)_ | 289.6 |
| _P99_ | 292.7ms |
| _P95_ | 292.6ms |
| _P50_ | 289.4ms |
| _End-to-end TPS_ | 307.14 tx/s |
| _Snapshots observed_ | 2 |
| _Per-snapshot TPS P50_ | 1323.00 tx/s |
| _Per-snapshot TPS P95_ | 2510.21 tx/s |
| _Per-snapshot TPS max_ | 2615.74 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      

## Nodes=3, Mixed, incremental ops off, wait for tx valid

Each client first grows its UTxO set (1-in to 2-out) for half of its tx budget, then contracts it back (2-in to 1-out) for the remainder.

| Number of nodes |  3 | 
| -- | -- |
| _Number of txs_ | 90 |
| _Avg. Confirmation Time (ms)_ | 46.4 |
| _P99_ | 70.0ms |
| _P95_ | 65.0ms |
| _P50_ | 46.2ms |
| _End-to-end TPS_ | 63.78 tx/s |
| _Snapshots observed_ | 61 |
| _Per-snapshot TPS P50_ | 62.51 tx/s |
| _Per-snapshot TPS P95_ | 124.57 tx/s |
| _Per-snapshot TPS max_ | 149.55 tx/s |
| _Number of Invalid txs_ | 0 |
| _Fanout outputs_        | 0 |
      
