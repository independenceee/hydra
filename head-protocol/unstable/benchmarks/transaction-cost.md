--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-12 04:15:05.167143948 UTC |
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
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6646 | 18.93 | 5.98 | 0.64 |
| 10| 7644 | 29.09 | 9.17 | 0.79 |
| 43| 14285 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10038 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 640 | 33.17 | 9.59 | 0.52 |
| 3 | 169 | 747 | 43.76 | 12.53 | 0.63 |
| 4 | 225 | 858 | 53.43 | 15.26 | 0.73 |
| 5 | 283 | 969 | 59.50 | 17.09 | 0.80 |
| 6 | 339 | 1081 | 69.99 | 20.10 | 0.91 |
| 7 | 396 | 1192 | 74.83 | 21.63 | 0.96 |
| 8 | 448 | 1307 | 96.27 | 27.12 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.77 | 8.48 | 0.49 |
| 3| 2016 | 26.36 | 9.59 | 0.52 |
| 5| 2477 | 32.44 | 12.63 | 0.61 |
| 10| 3190 | 41.74 | 18.57 | 0.76 |
| 40| 7680 | 97.98 | 54.21 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 22.54 | 7.31 | 0.41 |
| 2| 726 | 22.52 | 7.93 | 0.42 |
| 3| 857 | 24.03 | 9.02 | 0.45 |
| 5| 1320 | 32.24 | 12.66 | 0.56 |
| 10| 2110 | 41.77 | 18.66 | 0.72 |
| 42| 6699 | 99.08 | 55.89 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.13 | 8.90 | 0.48 |
| 2| 774 | 28.47 | 9.38 | 0.48 |
| 3| 971 | 30.90 | 10.74 | 0.52 |
| 5| 1267 | 35.01 | 13.24 | 0.58 |
| 10| 2009 | 44.94 | 19.38 | 0.74 |
| 34| 5597 | 97.12 | 49.97 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.83 | 10.15 | 0.53 |
| 2| 875 | 36.52 | 11.59 | 0.57 |
| 3| 984 | 38.59 | 12.82 | 0.60 |
| 5| 1220 | 41.89 | 15.05 | 0.65 |
| 10| 2224 | 56.83 | 22.65 | 0.87 |
| 28| 4760 | 96.54 | 45.62 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5783 | 27.04 | 9.07 | 0.69 |
| 2| 5945 | 35.88 | 12.05 | 0.79 |
| 3| 6175 | 45.84 | 15.47 | 0.90 |
| 4| 6344 | 56.13 | 18.96 | 1.02 |
| 5| 6363 | 60.41 | 20.28 | 1.06 |
| 6| 6637 | 71.99 | 24.32 | 1.20 |
| 7| 6716 | 82.20 | 27.73 | 1.31 |
| 8| 6831 | 90.65 | 30.45 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 284 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1138 | 6513 | 59.28 | 22.29 | 1.08 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

