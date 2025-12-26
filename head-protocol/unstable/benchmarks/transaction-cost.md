--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-26 04:46:59.601268302 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6641 | 19.08 | 6.04 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 226 | 862 | 49.55 | 14.29 | 0.69 |
| 5 | 282 | 974 | 61.07 | 17.49 | 0.81 |
| 6 | 339 | 1081 | 64.54 | 18.80 | 0.85 |
| 7 | 392 | 1192 | 72.30 | 20.90 | 0.94 |
| 8 | 451 | 1303 | 99.44 | 27.98 | 1.21 |
| 10 | 560 | 1525 | 97.63 | 28.31 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 23.92 | 7.60 | 0.48 |
| 2| 1975 | 26.55 | 9.00 | 0.52 |
| 3| 2056 | 26.94 | 9.77 | 0.53 |
| 5| 2326 | 29.97 | 11.95 | 0.58 |
| 10| 3194 | 40.86 | 18.32 | 0.75 |
| 40| 7743 | 99.60 | 54.64 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.57 | 7.31 | 0.41 |
| 2| 753 | 24.35 | 8.47 | 0.44 |
| 3| 916 | 27.10 | 9.90 | 0.48 |
| 5| 1279 | 31.09 | 12.36 | 0.55 |
| 10| 2017 | 39.68 | 18.08 | 0.69 |
| 43| 6841 | 99.21 | 56.63 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.50 | 8.46 | 0.46 |
| 2| 803 | 30.98 | 10.08 | 0.51 |
| 3| 902 | 30.26 | 10.55 | 0.51 |
| 5| 1354 | 38.49 | 14.22 | 0.62 |
| 10| 1996 | 47.56 | 20.07 | 0.77 |
| 34| 5853 | 95.16 | 49.51 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 33.87 | 10.16 | 0.53 |
| 2| 822 | 35.89 | 11.39 | 0.56 |
| 3| 892 | 37.13 | 12.38 | 0.58 |
| 5| 1320 | 43.20 | 15.46 | 0.67 |
| 10| 1998 | 53.91 | 21.77 | 0.83 |
| 29| 4795 | 97.43 | 46.53 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5838 | 27.00 | 9.07 | 0.69 |
| 2| 5893 | 32.64 | 10.90 | 0.75 |
| 3| 6113 | 45.49 | 15.35 | 0.90 |
| 4| 6339 | 55.95 | 18.89 | 1.02 |
| 5| 6463 | 66.12 | 22.38 | 1.13 |
| 6| 6521 | 74.84 | 25.32 | 1.22 |
| 7| 6543 | 74.73 | 25.04 | 1.22 |
| 8| 6725 | 88.50 | 29.78 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1139 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2276 | 7192 | 99.84 | 38.30 | 1.55 |

