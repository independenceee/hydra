--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-11 04:59:09.276909388 UTC |
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
| 1| 5836 | 10.28 | 3.25 | 0.51 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.79 | 5.94 | 0.64 |
| 10| 7650 | 29.09 | 9.17 | 0.79 |
| 43| 14279 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.34 | 9.90 | 0.53 |
| 3 | 170 | 747 | 40.01 | 11.63 | 0.59 |
| 4 | 225 | 858 | 52.73 | 15.12 | 0.72 |
| 5 | 281 | 969 | 61.29 | 17.58 | 0.81 |
| 6 | 338 | 1085 | 75.37 | 21.25 | 0.96 |
| 7 | 393 | 1192 | 82.73 | 23.48 | 1.04 |
| 8 | 449 | 1303 | 81.01 | 23.47 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1884 | 24.85 | 8.50 | 0.50 |
| 3| 2054 | 26.90 | 9.76 | 0.53 |
| 5| 2440 | 32.48 | 12.64 | 0.61 |
| 10| 3015 | 38.62 | 17.70 | 0.72 |
| 40| 7801 | 99.13 | 54.55 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 769 | 23.56 | 8.22 | 0.43 |
| 3| 909 | 25.06 | 9.31 | 0.46 |
| 5| 1188 | 28.05 | 11.48 | 0.51 |
| 10| 1985 | 39.65 | 18.07 | 0.69 |
| 42| 6785 | 99.17 | 55.95 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 27.54 | 8.47 | 0.46 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 944 | 30.94 | 10.75 | 0.52 |
| 5| 1321 | 35.53 | 13.41 | 0.59 |
| 10| 1895 | 42.69 | 18.70 | 0.71 |
| 36| 6001 | 96.69 | 51.20 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 947 | 37.84 | 12.60 | 0.59 |
| 5| 1241 | 42.65 | 15.28 | 0.66 |
| 10| 2105 | 55.44 | 22.23 | 0.85 |
| 28| 4716 | 96.13 | 45.54 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5828 | 27.08 | 9.09 | 0.69 |
| 2| 5922 | 36.15 | 12.14 | 0.79 |
| 3| 5970 | 40.43 | 13.48 | 0.84 |
| 4| 6352 | 56.07 | 18.96 | 1.02 |
| 5| 6544 | 66.22 | 22.42 | 1.13 |
| 6| 6626 | 75.09 | 25.33 | 1.23 |
| 7| 6885 | 87.13 | 29.43 | 1.37 |
| 8| 6952 | 93.03 | 31.30 | 1.43 |
| 9| 6887 | 93.89 | 31.62 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7161 | 99.38 | 38.04 | 1.54 |

