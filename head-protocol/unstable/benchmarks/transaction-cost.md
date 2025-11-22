--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-22 04:21:31.275410526 UTC |
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
| 1| 5837 | 10.26 | 3.25 | 0.51 |
| 2| 6037 | 12.99 | 4.13 | 0.55 |
| 3| 6242 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7648 | 29.18 | 9.20 | 0.79 |
| 43| 14285 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 43.64 | 12.49 | 0.63 |
| 4 | 226 | 858 | 52.52 | 15.02 | 0.72 |
| 5 | 284 | 969 | 57.93 | 16.68 | 0.78 |
| 6 | 339 | 1085 | 66.46 | 19.22 | 0.87 |
| 7 | 393 | 1192 | 74.77 | 21.58 | 0.96 |
| 8 | 451 | 1303 | 87.30 | 24.92 | 1.09 |
| 9 | 505 | 1414 | 91.24 | 26.32 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.43 | 8.40 | 0.49 |
| 3| 2065 | 26.90 | 9.76 | 0.53 |
| 5| 2414 | 32.41 | 12.62 | 0.61 |
| 10| 3291 | 42.79 | 18.87 | 0.78 |
| 42| 7896 | 99.88 | 56.09 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.81 | 7.37 | 0.42 |
| 2| 817 | 25.36 | 8.75 | 0.45 |
| 3| 998 | 26.02 | 9.58 | 0.47 |
| 5| 1191 | 30.12 | 12.07 | 0.53 |
| 10| 2140 | 41.90 | 18.70 | 0.72 |
| 41| 6635 | 98.03 | 54.97 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 27.50 | 8.46 | 0.46 |
| 2| 778 | 30.94 | 10.07 | 0.51 |
| 3| 914 | 32.76 | 11.24 | 0.54 |
| 5| 1323 | 38.45 | 14.21 | 0.62 |
| 10| 2069 | 48.30 | 20.29 | 0.78 |
| 37| 6081 | 99.57 | 52.71 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.87 | 10.16 | 0.53 |
| 2| 864 | 36.52 | 11.59 | 0.57 |
| 3| 1044 | 39.30 | 13.04 | 0.61 |
| 5| 1264 | 42.57 | 15.26 | 0.66 |
| 10| 2085 | 55.51 | 22.25 | 0.85 |
| 31| 4909 | 99.32 | 48.34 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 27.09 | 9.08 | 0.69 |
| 2| 5894 | 34.91 | 11.69 | 0.78 |
| 3| 6184 | 47.15 | 15.90 | 0.92 |
| 4| 6210 | 53.94 | 18.15 | 0.99 |
| 5| 6357 | 62.79 | 21.07 | 1.09 |
| 6| 6557 | 70.95 | 23.91 | 1.18 |
| 7| 6653 | 81.70 | 27.55 | 1.30 |
| 8| 6802 | 87.76 | 29.45 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 5 | 284 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2216 | 7155 | 98.49 | 37.73 | 1.53 |

