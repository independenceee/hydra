--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-23 12:41:45.858649772 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6243 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14286 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 43.59 | 12.49 | 0.63 |
| 4 | 225 | 862 | 48.23 | 13.99 | 0.68 |
| 5 | 285 | 969 | 56.32 | 16.36 | 0.77 |
| 6 | 338 | 1081 | 66.46 | 19.19 | 0.87 |
| 7 | 395 | 1196 | 76.05 | 21.92 | 0.98 |
| 8 | 449 | 1303 | 96.14 | 27.14 | 1.18 |
| 9 | 504 | 1414 | 98.00 | 27.93 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1885 | 24.85 | 8.50 | 0.50 |
| 3| 2108 | 28.09 | 10.09 | 0.54 |
| 5| 2462 | 33.24 | 12.86 | 0.62 |
| 10| 3125 | 40.98 | 18.35 | 0.75 |
| 41| 7804 | 99.77 | 55.38 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 22.81 | 7.38 | 0.42 |
| 2| 820 | 25.13 | 8.70 | 0.45 |
| 3| 857 | 24.03 | 9.02 | 0.45 |
| 5| 1115 | 26.98 | 11.18 | 0.50 |
| 10| 1952 | 39.71 | 18.08 | 0.69 |
| 40| 6383 | 95.77 | 53.66 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 29.13 | 8.90 | 0.48 |
| 2| 838 | 31.65 | 10.28 | 0.52 |
| 3| 1013 | 33.40 | 11.44 | 0.55 |
| 5| 1378 | 36.24 | 13.62 | 0.60 |
| 10| 2005 | 44.22 | 19.16 | 0.73 |
| 37| 6224 | 99.57 | 52.73 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 985 | 38.66 | 12.84 | 0.60 |
| 5| 1300 | 43.24 | 15.47 | 0.67 |
| 10| 2062 | 54.51 | 21.96 | 0.84 |
| 28| 4945 | 98.01 | 46.14 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 26.96 | 9.06 | 0.69 |
| 2| 6003 | 36.88 | 12.44 | 0.80 |
| 3| 5923 | 37.00 | 12.28 | 0.80 |
| 4| 6389 | 55.80 | 18.87 | 1.02 |
| 5| 6489 | 65.17 | 22.00 | 1.12 |
| 6| 6478 | 69.65 | 23.41 | 1.17 |
| 7| 6751 | 80.91 | 27.29 | 1.30 |
| 8| 7002 | 94.74 | 32.09 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6513 | 59.28 | 22.29 | 1.08 |
| 10 | 30 | 1706 | 6853 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |

