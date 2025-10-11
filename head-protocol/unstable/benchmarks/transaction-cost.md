--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-11 04:14:23.43625432 UTC |
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
| 1| 5834 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6243 | 14.78 | 4.68 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 29.49 | 9.31 | 0.79 |
| 43| 14281 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 747 | 42.34 | 12.19 | 0.61 |
| 4 | 225 | 858 | 50.85 | 14.62 | 0.70 |
| 5 | 282 | 969 | 63.52 | 18.15 | 0.84 |
| 6 | 337 | 1081 | 73.61 | 20.93 | 0.94 |
| 7 | 393 | 1192 | 72.75 | 21.09 | 0.94 |
| 8 | 450 | 1303 | 83.59 | 24.19 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1792 | 24.37 | 7.71 | 0.48 |
| 2| 1946 | 25.92 | 8.80 | 0.51 |
| 3| 2022 | 26.24 | 9.56 | 0.52 |
| 5| 2487 | 32.94 | 12.79 | 0.62 |
| 10| 3137 | 40.54 | 18.24 | 0.75 |
| 39| 7648 | 98.64 | 53.72 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.81 | 7.37 | 0.42 |
| 2| 789 | 23.59 | 8.23 | 0.43 |
| 3| 989 | 28.17 | 10.19 | 0.49 |
| 5| 1219 | 29.79 | 11.99 | 0.53 |
| 10| 2141 | 43.81 | 19.21 | 0.74 |
| 40| 6551 | 99.64 | 54.70 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 774 | 28.55 | 9.40 | 0.48 |
| 3| 961 | 30.98 | 10.76 | 0.52 |
| 5| 1254 | 35.04 | 13.25 | 0.58 |
| 10| 1988 | 47.21 | 19.98 | 0.76 |
| 35| 5702 | 95.20 | 50.15 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 874 | 36.60 | 11.61 | 0.57 |
| 3| 955 | 37.91 | 12.62 | 0.59 |
| 5| 1347 | 43.36 | 15.49 | 0.67 |
| 10| 2083 | 54.54 | 21.96 | 0.84 |
| 30| 4786 | 96.87 | 46.97 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.13 | 9.09 | 0.69 |
| 2| 6041 | 36.88 | 12.44 | 0.80 |
| 3| 6038 | 45.05 | 15.11 | 0.89 |
| 4| 6331 | 55.09 | 18.56 | 1.01 |
| 5| 6449 | 63.98 | 21.61 | 1.11 |
| 6| 6577 | 74.54 | 25.15 | 1.22 |
| 7| 6756 | 81.33 | 27.36 | 1.30 |
| 8| 6860 | 94.42 | 31.88 | 1.44 |
| 9| 6876 | 94.41 | 31.67 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 40.83 | 14.90 | 0.86 |
| 10 | 30 | 1706 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2163 | 7125 | 97.33 | 37.23 | 1.52 |

