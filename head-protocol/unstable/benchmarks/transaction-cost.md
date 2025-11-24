--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-24 04:44:12.879288054 UTC |
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
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7642 | 29.57 | 9.34 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 225 | 858 | 50.84 | 14.60 | 0.70 |
| 5 | 282 | 969 | 62.86 | 17.89 | 0.83 |
| 6 | 339 | 1081 | 74.88 | 21.12 | 0.96 |
| 7 | 397 | 1192 | 79.49 | 22.61 | 1.01 |
| 8 | 449 | 1303 | 85.20 | 24.42 | 1.07 |
| 10 | 560 | 1525 | 98.35 | 28.49 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.00 | 7.62 | 0.48 |
| 2| 1945 | 25.52 | 8.71 | 0.50 |
| 3| 2017 | 26.32 | 9.58 | 0.52 |
| 5| 2317 | 29.96 | 11.95 | 0.58 |
| 10| 3209 | 41.71 | 18.56 | 0.76 |
| 39| 7652 | 97.80 | 53.52 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 22.50 | 7.30 | 0.41 |
| 2| 792 | 23.55 | 8.22 | 0.43 |
| 3| 950 | 26.56 | 9.77 | 0.48 |
| 5| 1188 | 28.95 | 11.73 | 0.52 |
| 10| 1874 | 38.03 | 17.63 | 0.67 |
| 44| 6886 | 98.82 | 57.19 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.09 | 8.89 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 911 | 32.64 | 11.21 | 0.53 |
| 5| 1257 | 35.00 | 13.24 | 0.58 |
| 10| 2060 | 48.01 | 20.22 | 0.77 |
| 34| 5977 | 96.73 | 50.01 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.83 | 10.16 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 1017 | 38.62 | 12.83 | 0.60 |
| 5| 1275 | 42.64 | 15.28 | 0.66 |
| 10| 2155 | 55.39 | 22.23 | 0.85 |
| 29| 4678 | 94.81 | 45.76 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 26.92 | 9.04 | 0.69 |
| 2| 5995 | 36.97 | 12.46 | 0.80 |
| 3| 5945 | 40.32 | 13.45 | 0.83 |
| 4| 6334 | 56.09 | 18.93 | 1.02 |
| 5| 6473 | 64.82 | 21.92 | 1.12 |
| 6| 6605 | 74.50 | 25.19 | 1.22 |
| 7| 6851 | 84.36 | 28.45 | 1.34 |
| 8| 6728 | 87.90 | 29.47 | 1.37 |
| 9| 6978 | 99.53 | 33.54 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1141 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 81.81 | 31.06 | 1.34 |
| 10 | 38 | 2164 | 7127 | 96.88 | 37.08 | 1.51 |

