--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-18 04:16:34.703618879 UTC |
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
| 1| 5834 | 10.47 | 3.32 | 0.52 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.40 | 9.28 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10040 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.08 | 11.67 | 0.59 |
| 4 | 226 | 858 | 48.19 | 13.99 | 0.68 |
| 5 | 282 | 974 | 56.19 | 16.26 | 0.76 |
| 6 | 340 | 1085 | 66.55 | 19.24 | 0.87 |
| 7 | 395 | 1192 | 86.10 | 24.20 | 1.07 |
| 8 | 449 | 1307 | 96.25 | 27.07 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.37 | 7.71 | 0.48 |
| 2| 1942 | 25.88 | 8.79 | 0.51 |
| 3| 2129 | 27.94 | 10.05 | 0.54 |
| 5| 2427 | 31.96 | 12.51 | 0.61 |
| 10| 3075 | 38.80 | 17.74 | 0.73 |
| 38| 7403 | 95.00 | 52.07 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.80 | 7.38 | 0.41 |
| 2| 783 | 24.32 | 8.46 | 0.44 |
| 3| 931 | 27.07 | 9.88 | 0.48 |
| 5| 1273 | 30.19 | 12.08 | 0.54 |
| 10| 2082 | 40.37 | 18.27 | 0.70 |
| 42| 6694 | 98.89 | 55.84 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 28.42 | 8.68 | 0.47 |
| 2| 825 | 31.70 | 10.30 | 0.52 |
| 3| 924 | 32.72 | 11.23 | 0.54 |
| 5| 1313 | 35.72 | 13.46 | 0.59 |
| 10| 2107 | 48.85 | 20.47 | 0.79 |
| 36| 5905 | 97.50 | 51.46 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 33.12 | 9.94 | 0.52 |
| 2| 863 | 36.56 | 11.60 | 0.57 |
| 3| 1002 | 38.51 | 12.80 | 0.60 |
| 5| 1200 | 41.97 | 15.07 | 0.65 |
| 10| 2009 | 54.14 | 21.83 | 0.83 |
| 29| 4937 | 99.49 | 47.12 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.05 | 9.08 | 0.69 |
| 2| 5934 | 35.81 | 12.03 | 0.79 |
| 3| 6044 | 44.95 | 15.12 | 0.89 |
| 4| 6358 | 56.02 | 18.90 | 1.02 |
| 5| 6316 | 56.83 | 19.03 | 1.02 |
| 6| 6753 | 77.49 | 26.29 | 1.26 |
| 7| 6533 | 71.90 | 24.08 | 1.19 |
| 8| 6746 | 82.41 | 27.67 | 1.31 |
| 9| 7037 | 99.67 | 33.55 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1140 | 6515 | 60.61 | 22.74 | 1.09 |
| 10 | 40 | 2277 | 7194 | 99.66 | 38.24 | 1.55 |

