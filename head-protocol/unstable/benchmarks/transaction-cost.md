--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-30 04:15:18.242478408 UTC |
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
| 1| 5836 | 10.66 | 3.39 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 751 | 40.17 | 11.66 | 0.59 |
| 4 | 227 | 862 | 50.85 | 14.62 | 0.70 |
| 5 | 284 | 969 | 56.10 | 16.30 | 0.76 |
| 6 | 341 | 1081 | 74.84 | 21.15 | 0.95 |
| 7 | 393 | 1192 | 84.74 | 23.96 | 1.06 |
| 8 | 449 | 1303 | 80.71 | 23.40 | 1.03 |
| 9 | 504 | 1414 | 91.31 | 26.34 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.37 | 7.71 | 0.48 |
| 2| 1953 | 25.47 | 8.69 | 0.50 |
| 3| 2077 | 27.02 | 9.79 | 0.53 |
| 5| 2401 | 30.99 | 12.24 | 0.59 |
| 10| 3063 | 38.62 | 17.70 | 0.72 |
| 42| 7797 | 97.36 | 55.37 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.50 | 7.29 | 0.41 |
| 2| 837 | 25.53 | 8.80 | 0.46 |
| 3| 853 | 24.11 | 9.04 | 0.45 |
| 5| 1274 | 30.10 | 12.07 | 0.54 |
| 10| 1972 | 38.47 | 17.73 | 0.68 |
| 40| 6363 | 93.48 | 53.03 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 27.47 | 8.46 | 0.46 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 970 | 30.82 | 10.73 | 0.52 |
| 5| 1315 | 35.72 | 13.46 | 0.59 |
| 10| 1903 | 43.58 | 18.96 | 0.72 |
| 36| 6088 | 97.75 | 51.58 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 833 | 35.92 | 11.40 | 0.56 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1228 | 42.01 | 15.08 | 0.65 |
| 10| 1935 | 53.15 | 21.54 | 0.82 |
| 28| 4741 | 95.79 | 45.44 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5988 | 37.09 | 12.48 | 0.80 |
| 3| 6029 | 41.44 | 13.85 | 0.85 |
| 4| 6275 | 51.39 | 17.27 | 0.97 |
| 5| 6254 | 56.10 | 18.76 | 1.01 |
| 6| 6529 | 66.59 | 22.41 | 1.14 |
| 7| 6740 | 83.84 | 28.23 | 1.33 |
| 8| 6796 | 87.84 | 29.50 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 569 | 6173 | 40.58 | 14.82 | 0.86 |
| 10 | 20 | 1140 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1705 | 6852 | 79.34 | 30.22 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

