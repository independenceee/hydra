--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-23 04:43:54.29437991 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14286 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 747 | 42.72 | 12.29 | 0.62 |
| 4 | 227 | 858 | 49.81 | 14.40 | 0.69 |
| 5 | 282 | 969 | 56.24 | 16.34 | 0.77 |
| 6 | 340 | 1085 | 67.86 | 19.48 | 0.89 |
| 7 | 393 | 1196 | 79.21 | 22.73 | 1.01 |
| 8 | 448 | 1303 | 85.06 | 24.48 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1820 | 24.00 | 7.62 | 0.48 |
| 2| 1921 | 25.85 | 8.78 | 0.51 |
| 3| 2059 | 27.23 | 9.84 | 0.53 |
| 5| 2317 | 30.08 | 11.98 | 0.58 |
| 10| 3153 | 42.00 | 18.63 | 0.76 |
| 39| 7493 | 97.32 | 53.33 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.50 | 7.30 | 0.41 |
| 2| 722 | 22.60 | 7.95 | 0.42 |
| 3| 830 | 24.02 | 9.02 | 0.45 |
| 5| 1230 | 29.96 | 12.04 | 0.53 |
| 10| 1933 | 37.76 | 17.54 | 0.67 |
| 44| 6789 | 97.20 | 56.74 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 29.09 | 8.89 | 0.48 |
| 2| 771 | 28.47 | 9.38 | 0.48 |
| 3| 910 | 32.75 | 11.24 | 0.54 |
| 5| 1388 | 36.51 | 13.69 | 0.61 |
| 10| 1908 | 46.80 | 19.84 | 0.76 |
| 35| 5870 | 97.00 | 50.66 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.79 | 10.15 | 0.53 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1158 | 41.11 | 14.82 | 0.64 |
| 10| 2318 | 57.35 | 22.82 | 0.88 |
| 29| 4978 | 99.30 | 47.09 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 26.97 | 9.05 | 0.69 |
| 2| 5868 | 34.88 | 11.66 | 0.77 |
| 3| 6118 | 44.84 | 15.09 | 0.89 |
| 4| 6089 | 46.96 | 15.68 | 0.91 |
| 5| 6380 | 64.05 | 21.56 | 1.10 |
| 6| 6385 | 64.77 | 21.66 | 1.11 |
| 7| 6732 | 81.40 | 27.47 | 1.30 |
| 8| 7013 | 96.65 | 32.68 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 569 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2218 | 7157 | 98.05 | 37.58 | 1.53 |

