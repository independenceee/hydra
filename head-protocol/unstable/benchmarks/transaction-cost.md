--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-03 04:38:43.918944486 UTC |
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
| 1| 5836 | 10.69 | 3.40 | 0.52 |
| 2| 6037 | 12.42 | 3.93 | 0.54 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 751 | 41.12 | 11.90 | 0.60 |
| 4 | 226 | 862 | 54.17 | 15.47 | 0.74 |
| 5 | 282 | 974 | 61.69 | 17.65 | 0.82 |
| 6 | 339 | 1081 | 73.61 | 20.90 | 0.94 |
| 7 | 392 | 1192 | 86.31 | 24.25 | 1.07 |
| 8 | 449 | 1303 | 88.32 | 25.37 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.29 | 7.69 | 0.48 |
| 2| 1886 | 24.77 | 8.48 | 0.49 |
| 3| 2127 | 28.09 | 10.09 | 0.54 |
| 5| 2451 | 31.94 | 12.51 | 0.61 |
| 10| 3181 | 42.22 | 18.69 | 0.77 |
| 40| 7600 | 97.48 | 54.09 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.57 | 7.33 | 0.41 |
| 2| 697 | 22.62 | 7.95 | 0.42 |
| 3| 967 | 26.86 | 9.84 | 0.48 |
| 5| 1206 | 29.10 | 11.79 | 0.52 |
| 10| 1999 | 39.75 | 18.08 | 0.69 |
| 42| 6498 | 98.05 | 55.61 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 597 | 28.46 | 8.69 | 0.47 |
| 2| 877 | 29.97 | 9.84 | 0.50 |
| 3| 976 | 30.90 | 10.74 | 0.52 |
| 5| 1269 | 35.04 | 13.25 | 0.58 |
| 10| 2154 | 46.40 | 19.82 | 0.76 |
| 37| 6008 | 97.66 | 52.20 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.83 | 10.15 | 0.53 |
| 2| 760 | 35.14 | 11.16 | 0.55 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1260 | 42.68 | 15.29 | 0.66 |
| 10| 2026 | 54.14 | 21.83 | 0.83 |
| 29| 5035 | 99.92 | 47.26 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5802 | 27.16 | 9.11 | 0.69 |
| 2| 6019 | 36.73 | 12.41 | 0.80 |
| 3| 6108 | 44.87 | 15.07 | 0.89 |
| 4| 6311 | 56.44 | 19.06 | 1.02 |
| 5| 6486 | 64.76 | 21.88 | 1.12 |
| 6| 6534 | 71.96 | 24.20 | 1.19 |
| 7| 6913 | 85.70 | 28.98 | 1.36 |
| 8| 6938 | 94.11 | 31.85 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.52 | 6.86 | 0.62 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 37 | 2105 | 7091 | 93.95 | 35.96 | 1.48 |

