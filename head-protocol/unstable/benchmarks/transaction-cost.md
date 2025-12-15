--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-15 04:52:15.621252384 UTC |
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
| 1| 5836 | 10.36 | 3.28 | 0.51 |
| 2| 6037 | 13.10 | 4.17 | 0.55 |
| 3| 6238 | 14.90 | 4.72 | 0.58 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10079 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 640 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 43.53 | 12.46 | 0.62 |
| 4 | 226 | 858 | 48.97 | 14.17 | 0.69 |
| 5 | 282 | 969 | 61.56 | 17.62 | 0.82 |
| 6 | 337 | 1081 | 75.52 | 21.36 | 0.96 |
| 7 | 397 | 1192 | 86.75 | 24.40 | 1.08 |
| 8 | 450 | 1303 | 85.03 | 24.48 | 1.07 |
| 9 | 505 | 1414 | 96.65 | 27.67 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.29 | 7.69 | 0.48 |
| 2| 2008 | 26.76 | 9.04 | 0.52 |
| 3| 2101 | 28.43 | 10.17 | 0.55 |
| 5| 2379 | 31.34 | 12.32 | 0.60 |
| 10| 3206 | 41.52 | 18.51 | 0.76 |
| 39| 7453 | 94.01 | 52.43 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 22.54 | 7.31 | 0.41 |
| 2| 818 | 25.14 | 8.70 | 0.45 |
| 3| 930 | 26.71 | 9.79 | 0.48 |
| 5| 1244 | 29.52 | 11.93 | 0.53 |
| 10| 1913 | 38.03 | 17.62 | 0.67 |
| 42| 6643 | 96.84 | 55.30 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 869 | 29.94 | 9.83 | 0.50 |
| 3| 962 | 33.51 | 11.46 | 0.55 |
| 5| 1225 | 34.22 | 13.01 | 0.57 |
| 10| 1995 | 48.00 | 20.22 | 0.77 |
| 37| 6018 | 99.46 | 52.66 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 824 | 35.92 | 11.40 | 0.56 |
| 3| 994 | 38.63 | 12.83 | 0.60 |
| 5| 1396 | 43.65 | 15.58 | 0.68 |
| 10| 1980 | 53.19 | 21.55 | 0.82 |
| 29| 4792 | 97.27 | 46.49 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 27.13 | 9.10 | 0.69 |
| 2| 5894 | 34.95 | 11.69 | 0.78 |
| 3| 6143 | 45.89 | 15.46 | 0.90 |
| 4| 6185 | 51.25 | 17.24 | 0.96 |
| 5| 6400 | 63.81 | 21.55 | 1.10 |
| 6| 6532 | 73.51 | 24.75 | 1.21 |
| 7| 6597 | 77.58 | 26.02 | 1.25 |
| 8| 7089 | 96.04 | 32.52 | 1.47 |
| 9| 7091 | 97.86 | 33.05 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 568 | 6172 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1707 | 6854 | 79.78 | 30.37 | 1.32 |
| 10 | 39 | 2219 | 7159 | 97.61 | 37.43 | 1.52 |

