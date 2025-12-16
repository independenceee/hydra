--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-16 04:45:54.450609598 UTC |
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
| 1| 5834 | 10.76 | 3.42 | 0.52 |
| 2| 6042 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10078 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 171 | 747 | 39.82 | 11.57 | 0.59 |
| 4 | 227 | 858 | 49.33 | 14.23 | 0.69 |
| 5 | 282 | 974 | 60.84 | 17.38 | 0.81 |
| 6 | 338 | 1085 | 71.76 | 20.45 | 0.93 |
| 7 | 393 | 1192 | 76.87 | 22.12 | 0.98 |
| 8 | 450 | 1303 | 89.31 | 25.41 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1818 | 24.37 | 7.71 | 0.48 |
| 2| 1925 | 25.88 | 8.79 | 0.51 |
| 3| 2064 | 27.27 | 9.85 | 0.53 |
| 5| 2468 | 32.53 | 12.65 | 0.61 |
| 10| 3127 | 40.60 | 18.25 | 0.75 |
| 43| 7785 | 98.00 | 56.22 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.57 | 7.31 | 0.41 |
| 2| 789 | 25.16 | 8.71 | 0.45 |
| 3| 884 | 25.05 | 9.30 | 0.46 |
| 5| 1258 | 28.96 | 11.74 | 0.52 |
| 10| 1989 | 40.39 | 18.29 | 0.70 |
| 41| 6504 | 95.40 | 54.26 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.50 | 8.46 | 0.46 |
| 2| 827 | 29.19 | 9.60 | 0.49 |
| 3| 961 | 30.98 | 10.76 | 0.52 |
| 5| 1253 | 36.90 | 13.75 | 0.60 |
| 10| 2054 | 48.27 | 20.28 | 0.78 |
| 37| 5990 | 97.44 | 52.10 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.83 | 10.15 | 0.53 |
| 2| 813 | 35.85 | 11.38 | 0.56 |
| 3| 980 | 38.59 | 12.82 | 0.60 |
| 5| 1244 | 42.64 | 15.28 | 0.66 |
| 10| 2102 | 54.85 | 22.04 | 0.84 |
| 30| 4948 | 99.84 | 47.85 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.05 | 9.07 | 0.69 |
| 2| 5961 | 35.87 | 12.06 | 0.79 |
| 3| 5966 | 37.85 | 12.60 | 0.81 |
| 4| 6353 | 55.96 | 18.88 | 1.02 |
| 5| 6458 | 64.25 | 21.72 | 1.11 |
| 6| 6718 | 76.20 | 25.79 | 1.25 |
| 7| 6725 | 83.34 | 28.14 | 1.32 |
| 8| 6905 | 91.19 | 30.70 | 1.41 |
| 9| 7009 | 96.80 | 32.62 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1711 | 6858 | 81.11 | 30.83 | 1.33 |
| 10 | 38 | 2165 | 7127 | 96.88 | 37.08 | 1.51 |

