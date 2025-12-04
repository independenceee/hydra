--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-04 04:39:48.228390729 UTC |
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
| 1| 5840 | 10.85 | 3.45 | 0.52 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 169 | 747 | 43.59 | 12.49 | 0.63 |
| 4 | 227 | 862 | 51.13 | 14.69 | 0.71 |
| 5 | 283 | 969 | 59.87 | 17.18 | 0.80 |
| 6 | 338 | 1085 | 74.76 | 21.13 | 0.95 |
| 7 | 394 | 1192 | 76.33 | 21.90 | 0.98 |
| 8 | 450 | 1303 | 87.97 | 25.24 | 1.10 |
| 9 | 506 | 1414 | 98.18 | 27.87 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.00 | 7.62 | 0.48 |
| 2| 1936 | 25.85 | 8.78 | 0.51 |
| 3| 2055 | 26.99 | 9.78 | 0.53 |
| 5| 2452 | 33.14 | 12.84 | 0.62 |
| 10| 3156 | 41.23 | 18.41 | 0.75 |
| 41| 7763 | 98.49 | 55.01 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.81 | 7.37 | 0.42 |
| 2| 806 | 25.59 | 8.81 | 0.46 |
| 3| 934 | 26.63 | 9.77 | 0.48 |
| 5| 1158 | 28.08 | 11.49 | 0.51 |
| 10| 1941 | 38.38 | 17.70 | 0.67 |
| 44| 6930 | 99.19 | 57.29 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.17 | 8.91 | 0.48 |
| 2| 779 | 30.98 | 10.08 | 0.51 |
| 3| 864 | 32.01 | 11.01 | 0.53 |
| 5| 1285 | 34.94 | 13.22 | 0.58 |
| 10| 2233 | 50.40 | 20.93 | 0.81 |
| 37| 6021 | 97.52 | 52.13 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.83 | 10.15 | 0.53 |
| 2| 869 | 36.60 | 11.61 | 0.57 |
| 3| 1006 | 38.51 | 12.80 | 0.60 |
| 5| 1194 | 41.90 | 15.05 | 0.65 |
| 10| 2097 | 54.50 | 21.96 | 0.84 |
| 29| 4731 | 96.37 | 46.19 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.13 | 9.10 | 0.69 |
| 2| 5914 | 36.01 | 12.10 | 0.79 |
| 3| 6051 | 41.28 | 13.83 | 0.85 |
| 4| 6267 | 55.02 | 18.51 | 1.00 |
| 5| 6458 | 65.19 | 21.96 | 1.12 |
| 6| 6437 | 68.25 | 22.89 | 1.15 |
| 7| 6665 | 82.09 | 27.62 | 1.31 |
| 8| 6862 | 91.51 | 30.95 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2220 | 7160 | 98.93 | 37.88 | 1.54 |

