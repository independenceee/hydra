--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-13 04:14:32.640406513 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6236 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.88 | 9.10 | 0.79 |
| 43| 14283 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 169 | 751 | 39.98 | 11.61 | 0.59 |
| 4 | 226 | 858 | 49.59 | 14.30 | 0.69 |
| 5 | 282 | 969 | 56.61 | 16.40 | 0.77 |
| 6 | 339 | 1081 | 65.99 | 19.03 | 0.87 |
| 7 | 394 | 1192 | 86.92 | 24.53 | 1.08 |
| 8 | 450 | 1303 | 92.44 | 26.35 | 1.14 |
| 9 | 505 | 1414 | 99.04 | 28.19 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.00 | 7.62 | 0.48 |
| 2| 1929 | 25.92 | 8.80 | 0.51 |
| 3| 2095 | 27.39 | 9.88 | 0.54 |
| 5| 2322 | 30.37 | 12.05 | 0.58 |
| 10| 3218 | 42.36 | 18.76 | 0.77 |
| 39| 7601 | 97.58 | 53.42 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.80 | 7.37 | 0.41 |
| 2| 726 | 22.56 | 7.94 | 0.42 |
| 3| 949 | 26.14 | 9.61 | 0.47 |
| 5| 1263 | 31.37 | 12.43 | 0.55 |
| 10| 2081 | 40.59 | 18.34 | 0.70 |
| 42| 6642 | 98.39 | 55.72 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 27.51 | 8.47 | 0.46 |
| 2| 802 | 30.98 | 10.08 | 0.51 |
| 3| 906 | 30.26 | 10.55 | 0.51 |
| 5| 1255 | 35.01 | 13.24 | 0.58 |
| 10| 2012 | 44.30 | 19.18 | 0.74 |
| 36| 5862 | 95.96 | 50.98 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.16 | 0.53 |
| 2| 852 | 36.60 | 11.61 | 0.57 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1204 | 41.97 | 15.07 | 0.65 |
| 10| 2004 | 54.17 | 21.84 | 0.83 |
| 29| 5014 | 99.48 | 47.19 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 23.01 | 7.58 | 0.64 |
| 2| 5941 | 35.80 | 12.03 | 0.79 |
| 3| 6114 | 44.87 | 15.06 | 0.89 |
| 4| 6174 | 52.74 | 17.66 | 0.98 |
| 5| 6473 | 64.63 | 21.84 | 1.11 |
| 6| 6571 | 73.39 | 24.67 | 1.21 |
| 7| 6776 | 82.74 | 27.98 | 1.32 |
| 8| 7096 | 96.61 | 32.76 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1139 | 6513 | 59.47 | 22.36 | 1.08 |
| 10 | 30 | 1706 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2217 | 7156 | 98.05 | 37.58 | 1.53 |

