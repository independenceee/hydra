--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-17 05:39:07.952655632 UTC |
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
| 1| 5837 | 10.76 | 3.42 | 0.52 |
| 2| 6042 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 29.57 | 9.34 | 0.79 |
| 43| 14279 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 41.39 | 11.95 | 0.60 |
| 4 | 227 | 858 | 53.74 | 15.29 | 0.73 |
| 5 | 283 | 969 | 59.86 | 17.18 | 0.80 |
| 6 | 337 | 1081 | 65.63 | 18.94 | 0.86 |
| 7 | 396 | 1192 | 72.02 | 20.91 | 0.94 |
| 8 | 449 | 1307 | 80.21 | 23.22 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1921 | 25.84 | 8.78 | 0.51 |
| 3| 2141 | 28.39 | 10.16 | 0.55 |
| 5| 2446 | 32.11 | 12.55 | 0.61 |
| 10| 3031 | 38.60 | 17.69 | 0.72 |
| 41| 7686 | 96.94 | 54.58 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.80 | 7.37 | 0.41 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 914 | 25.02 | 9.30 | 0.46 |
| 5| 1115 | 27.12 | 11.22 | 0.50 |
| 10| 1882 | 37.65 | 17.51 | 0.66 |
| 41| 6456 | 94.47 | 53.97 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 27.47 | 8.46 | 0.46 |
| 2| 819 | 29.19 | 9.60 | 0.49 |
| 3| 902 | 30.26 | 10.55 | 0.51 |
| 5| 1287 | 34.94 | 13.22 | 0.58 |
| 10| 1987 | 47.32 | 20.01 | 0.76 |
| 34| 5653 | 94.00 | 49.20 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.16 | 0.53 |
| 2| 835 | 35.92 | 11.40 | 0.56 |
| 3| 1033 | 38.58 | 12.82 | 0.60 |
| 5| 1342 | 43.36 | 15.49 | 0.67 |
| 10| 2118 | 55.45 | 22.23 | 0.85 |
| 29| 4897 | 99.22 | 47.03 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5823 | 27.08 | 9.08 | 0.69 |
| 2| 5945 | 35.91 | 12.06 | 0.79 |
| 3| 6026 | 41.40 | 13.84 | 0.85 |
| 4| 6186 | 50.14 | 16.80 | 0.95 |
| 5| 6291 | 59.49 | 19.94 | 1.05 |
| 6| 6462 | 68.08 | 22.85 | 1.15 |
| 7| 6843 | 84.68 | 28.59 | 1.34 |
| 8| 6998 | 95.86 | 32.32 | 1.47 |
| 9| 6896 | 97.05 | 32.55 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6174 | 40.83 | 14.90 | 0.86 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2216 | 7156 | 98.49 | 37.73 | 1.53 |

