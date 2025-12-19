--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-19 04:44:43.733687397 UTC |
| _Max. memory units_ | 14000000 |
| _Max. CPU units_ | 10000000000 |
| _Max. tx size (kB)_ | 16384 |

## Script summary

| Name   | Hash | Size (Bytes) 
| :----- | :--- | -----------: 
| νInitial | c8a101a5c8ac4816b0dceb59ce31fc2258e387de828f02961d2f2045 | 2652 | 
| νCommit | 61458bc2f297fff3cc5df6ac7ab57cefd87763b0b7bd722146a1035c | 685 | 
| νHead | a1442faf26d4ec409e2f62a685c1d4893f8d6bcbaf7bcb59d6fa1340 | 14599 | 
| μHead | fd173b993e12103cd734ca6710d364e17120a5eb37a224c64ab2b188* | 5284 | 
| νDeposit | ae01dade3a9c346d5c93ae3ce339412b90a0b8f83f94ec6baa24e30c | 1102 | 

* The minting policy hash is only usable for comparison. As the script is parameterized, the actual script is unique per head.

## `Init` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6240 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 99.06 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 169 | 747 | 40.17 | 11.66 | 0.59 |
| 4 | 228 | 858 | 52.32 | 14.97 | 0.72 |
| 5 | 282 | 969 | 63.29 | 18.06 | 0.83 |
| 6 | 337 | 1085 | 69.44 | 19.82 | 0.90 |
| 7 | 395 | 1192 | 83.13 | 23.66 | 1.04 |
| 8 | 448 | 1303 | 98.12 | 27.56 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.00 | 7.62 | 0.48 |
| 2| 2008 | 26.62 | 9.02 | 0.52 |
| 3| 2155 | 28.52 | 10.22 | 0.55 |
| 5| 2480 | 33.37 | 12.89 | 0.62 |
| 10| 3089 | 39.94 | 18.05 | 0.74 |
| 38| 7382 | 96.43 | 52.42 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.80 | 7.38 | 0.42 |
| 2| 771 | 23.65 | 8.24 | 0.43 |
| 3| 950 | 27.06 | 9.90 | 0.48 |
| 5| 1181 | 29.14 | 11.80 | 0.52 |
| 10| 1935 | 38.70 | 17.80 | 0.68 |
| 40| 6404 | 94.35 | 53.27 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.47 | 8.46 | 0.46 |
| 2| 805 | 29.26 | 9.62 | 0.49 |
| 3| 1024 | 33.99 | 11.62 | 0.55 |
| 5| 1274 | 37.65 | 13.97 | 0.61 |
| 10| 2014 | 44.04 | 19.11 | 0.73 |
| 37| 6253 | 99.36 | 52.70 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.16 | 0.53 |
| 2| 807 | 35.88 | 11.39 | 0.56 |
| 3| 1036 | 39.34 | 13.05 | 0.61 |
| 5| 1405 | 44.07 | 15.71 | 0.68 |
| 10| 2036 | 53.75 | 21.73 | 0.83 |
| 29| 4941 | 99.67 | 47.18 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.00 | 9.08 | 0.69 |
| 2| 5942 | 35.80 | 12.04 | 0.79 |
| 3| 6126 | 45.77 | 15.42 | 0.90 |
| 4| 6213 | 51.58 | 17.33 | 0.97 |
| 5| 6361 | 60.20 | 20.31 | 1.06 |
| 6| 6668 | 75.32 | 25.35 | 1.23 |
| 7| 6868 | 87.71 | 29.66 | 1.37 |
| 8| 6918 | 94.78 | 32.00 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5867 | 19.45 | 6.61 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1711 | 6857 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.49 | 37.73 | 1.53 |

