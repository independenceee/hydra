--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-09-30 04:14:17.478334916 UTC |
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
| 1| 5837 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6646 | 19.08 | 6.04 | 0.64 |
| 10| 7644 | 29.02 | 9.14 | 0.79 |
| 43| 14279 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 41.08 | 11.87 | 0.60 |
| 4 | 227 | 858 | 52.46 | 15.01 | 0.72 |
| 5 | 283 | 974 | 62.16 | 17.69 | 0.82 |
| 6 | 340 | 1081 | 67.94 | 19.57 | 0.89 |
| 7 | 395 | 1192 | 74.55 | 21.48 | 0.96 |
| 8 | 450 | 1303 | 81.90 | 23.58 | 1.04 |
| 9 | 504 | 1414 | 89.42 | 25.89 | 1.12 |
| 10 | 560 | 1525 | 96.87 | 28.12 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.37 | 7.71 | 0.48 |
| 2| 1930 | 25.84 | 8.78 | 0.51 |
| 3| 2017 | 26.24 | 9.56 | 0.52 |
| 5| 2326 | 30.08 | 11.98 | 0.58 |
| 10| 3004 | 37.97 | 17.50 | 0.72 |
| 39| 7478 | 95.14 | 52.73 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 22.50 | 7.30 | 0.41 |
| 2| 804 | 24.25 | 8.45 | 0.44 |
| 3| 928 | 26.95 | 9.85 | 0.48 |
| 5| 1292 | 30.57 | 12.21 | 0.54 |
| 10| 1945 | 37.62 | 17.49 | 0.67 |
| 41| 6465 | 96.73 | 54.63 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.09 | 8.89 | 0.48 |
| 2| 789 | 30.94 | 10.07 | 0.51 |
| 3| 979 | 30.87 | 10.74 | 0.52 |
| 5| 1435 | 37.11 | 13.88 | 0.61 |
| 10| 2009 | 47.43 | 20.04 | 0.77 |
| 33| 5740 | 94.51 | 48.69 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 33.83 | 10.16 | 0.53 |
| 2| 810 | 35.92 | 11.40 | 0.56 |
| 3| 1058 | 39.34 | 13.05 | 0.61 |
| 5| 1341 | 43.32 | 15.49 | 0.67 |
| 10| 1986 | 53.79 | 21.74 | 0.83 |
| 29| 4933 | 98.54 | 46.86 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.08 | 9.09 | 0.69 |
| 2| 5874 | 34.88 | 11.68 | 0.77 |
| 3| 6091 | 44.80 | 15.04 | 0.89 |
| 4| 6231 | 53.92 | 18.12 | 0.99 |
| 5| 6457 | 65.06 | 21.94 | 1.12 |
| 6| 6645 | 74.43 | 25.15 | 1.23 |
| 7| 6743 | 83.07 | 28.01 | 1.32 |
| 8| 6943 | 90.42 | 30.46 | 1.41 |
| 9| 6938 | 98.36 | 33.07 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2162 | 7124 | 96.63 | 36.99 | 1.51 |

