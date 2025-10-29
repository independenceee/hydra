--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-29 04:30:29.357006258 UTC |
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
| 1| 5837 | 10.36 | 3.28 | 0.51 |
| 2| 6041 | 12.44 | 3.94 | 0.54 |
| 3| 6242 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.96 | 6.00 | 0.64 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14279 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 168 | 747 | 42.75 | 12.31 | 0.62 |
| 4 | 228 | 858 | 50.91 | 14.61 | 0.70 |
| 5 | 283 | 969 | 56.69 | 16.51 | 0.77 |
| 6 | 340 | 1085 | 73.61 | 20.86 | 0.94 |
| 7 | 394 | 1192 | 74.88 | 21.64 | 0.96 |
| 8 | 450 | 1303 | 93.65 | 26.49 | 1.16 |
| 9 | 504 | 1414 | 92.98 | 26.86 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.40 | 8.40 | 0.49 |
| 3| 2056 | 27.35 | 9.87 | 0.53 |
| 5| 2365 | 31.37 | 12.33 | 0.60 |
| 10| 3177 | 41.96 | 18.62 | 0.76 |
| 40| 7373 | 94.56 | 53.20 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.84 | 7.38 | 0.42 |
| 2| 815 | 25.39 | 8.76 | 0.45 |
| 3| 960 | 27.08 | 9.89 | 0.48 |
| 5| 1302 | 30.40 | 12.17 | 0.54 |
| 10| 2174 | 43.40 | 19.11 | 0.73 |
| 42| 6390 | 92.72 | 54.14 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.13 | 8.90 | 0.48 |
| 2| 889 | 29.90 | 9.82 | 0.50 |
| 3| 966 | 30.86 | 10.73 | 0.52 |
| 5| 1347 | 38.38 | 14.19 | 0.62 |
| 10| 2048 | 45.56 | 19.57 | 0.75 |
| 36| 5943 | 96.67 | 51.24 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 823 | 35.85 | 11.38 | 0.56 |
| 3| 1055 | 39.26 | 13.03 | 0.61 |
| 5| 1384 | 43.88 | 15.66 | 0.68 |
| 10| 2003 | 53.91 | 21.77 | 0.83 |
| 29| 4971 | 99.31 | 47.09 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 27.08 | 9.09 | 0.69 |
| 2| 6023 | 36.93 | 12.44 | 0.80 |
| 3| 6037 | 45.11 | 15.18 | 0.89 |
| 4| 6342 | 56.95 | 19.26 | 1.03 |
| 5| 6454 | 61.98 | 20.92 | 1.09 |
| 6| 6507 | 72.10 | 24.20 | 1.19 |
| 7| 6698 | 80.57 | 27.09 | 1.29 |
| 8| 6825 | 92.54 | 31.20 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2217 | 7156 | 99.82 | 38.19 | 1.55 |

