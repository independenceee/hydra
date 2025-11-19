--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-19 04:32:45.840009993 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.79 | 4.69 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 751 | 43.68 | 12.51 | 0.63 |
| 4 | 227 | 858 | 49.18 | 14.22 | 0.69 |
| 5 | 284 | 969 | 59.33 | 17.05 | 0.80 |
| 6 | 338 | 1081 | 64.44 | 18.70 | 0.85 |
| 7 | 394 | 1192 | 80.32 | 22.86 | 1.02 |
| 8 | 450 | 1303 | 91.61 | 26.00 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.29 | 7.69 | 0.48 |
| 2| 1953 | 25.51 | 8.70 | 0.51 |
| 3| 2012 | 25.95 | 9.49 | 0.52 |
| 5| 2377 | 31.57 | 12.38 | 0.60 |
| 10| 3078 | 39.75 | 18.01 | 0.74 |
| 41| 7782 | 99.87 | 55.43 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 22.81 | 7.38 | 0.42 |
| 2| 762 | 24.28 | 8.45 | 0.44 |
| 3| 933 | 26.98 | 9.87 | 0.48 |
| 5| 1230 | 29.19 | 11.80 | 0.53 |
| 10| 2042 | 39.56 | 18.05 | 0.69 |
| 40| 6652 | 98.30 | 54.37 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 898 | 30.15 | 10.52 | 0.51 |
| 5| 1247 | 36.95 | 13.76 | 0.60 |
| 10| 2041 | 45.45 | 19.54 | 0.75 |
| 35| 5684 | 93.38 | 49.61 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.83 | 10.15 | 0.53 |
| 2| 818 | 35.85 | 11.38 | 0.56 |
| 3| 895 | 37.20 | 12.40 | 0.58 |
| 5| 1246 | 42.61 | 15.27 | 0.66 |
| 10| 2209 | 56.24 | 22.47 | 0.86 |
| 27| 4713 | 95.63 | 44.76 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 23.01 | 7.58 | 0.64 |
| 2| 5918 | 32.57 | 10.89 | 0.75 |
| 3| 6057 | 42.29 | 14.20 | 0.86 |
| 4| 6163 | 50.37 | 16.88 | 0.95 |
| 5| 6326 | 58.22 | 19.53 | 1.04 |
| 6| 6584 | 71.74 | 24.20 | 1.19 |
| 7| 6732 | 79.91 | 26.85 | 1.29 |
| 8| 7072 | 95.76 | 32.40 | 1.47 |
| 9| 6981 | 98.19 | 33.01 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 20 | 1137 | 6511 | 61.05 | 22.90 | 1.10 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2223 | 7162 | 99.38 | 38.04 | 1.54 |

