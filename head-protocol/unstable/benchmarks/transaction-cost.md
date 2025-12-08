--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-08 04:35:02.98393046 UTC |
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
| 1| 5836 | 10.67 | 3.39 | 0.52 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6645 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14286 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1271 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10044 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 169 | 747 | 40.25 | 11.70 | 0.59 |
| 4 | 227 | 858 | 49.83 | 14.40 | 0.69 |
| 5 | 283 | 969 | 57.42 | 16.56 | 0.78 |
| 6 | 339 | 1085 | 64.63 | 18.75 | 0.86 |
| 7 | 395 | 1192 | 84.46 | 23.89 | 1.06 |
| 8 | 448 | 1303 | 87.20 | 24.95 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.29 | 7.69 | 0.48 |
| 2| 1944 | 25.55 | 8.71 | 0.51 |
| 3| 2179 | 29.09 | 10.37 | 0.56 |
| 5| 2400 | 32.00 | 12.52 | 0.60 |
| 10| 3223 | 41.89 | 18.61 | 0.76 |
| 41| 7666 | 97.86 | 54.85 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.57 | 7.31 | 0.41 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 958 | 26.67 | 9.80 | 0.48 |
| 5| 1170 | 27.97 | 11.46 | 0.51 |
| 10| 2067 | 40.66 | 18.34 | 0.70 |
| 40| 6489 | 96.36 | 53.85 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 29.17 | 8.91 | 0.48 |
| 2| 827 | 29.22 | 9.61 | 0.49 |
| 3| 910 | 32.72 | 11.23 | 0.54 |
| 5| 1321 | 35.75 | 13.46 | 0.59 |
| 10| 1862 | 42.69 | 18.70 | 0.71 |
| 36| 5847 | 96.71 | 51.23 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 799 | 35.92 | 11.40 | 0.56 |
| 3| 895 | 37.20 | 12.40 | 0.58 |
| 5| 1251 | 42.64 | 15.28 | 0.66 |
| 10| 1980 | 53.83 | 21.73 | 0.83 |
| 29| 4865 | 97.77 | 46.61 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 26.92 | 9.04 | 0.69 |
| 2| 5935 | 35.84 | 12.03 | 0.79 |
| 3| 6188 | 45.81 | 15.45 | 0.90 |
| 4| 6212 | 54.21 | 18.23 | 0.99 |
| 5| 6381 | 60.36 | 20.28 | 1.06 |
| 6| 6616 | 74.53 | 25.11 | 1.22 |
| 7| 6794 | 84.32 | 28.49 | 1.34 |
| 8| 6781 | 87.40 | 29.39 | 1.37 |
| 9| 6921 | 96.29 | 32.34 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 569 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1140 | 6515 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 40 | 2281 | 7197 | 99.22 | 38.09 | 1.54 |

