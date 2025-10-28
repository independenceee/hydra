--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-28 04:18:55.013773428 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 18.98 | 6.00 | 0.64 |
| 10| 7646 | 29.23 | 9.22 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10079 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 41.18 | 11.91 | 0.60 |
| 4 | 225 | 858 | 48.25 | 14.05 | 0.68 |
| 5 | 282 | 974 | 59.37 | 17.03 | 0.80 |
| 6 | 338 | 1081 | 66.16 | 19.11 | 0.87 |
| 7 | 395 | 1192 | 84.88 | 24.00 | 1.06 |
| 8 | 451 | 1303 | 87.22 | 24.90 | 1.09 |
| 9 | 506 | 1414 | 98.84 | 28.19 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1982 | 26.47 | 8.98 | 0.52 |
| 3| 2013 | 25.98 | 9.50 | 0.52 |
| 5| 2317 | 30.00 | 11.96 | 0.58 |
| 10| 3028 | 38.78 | 17.73 | 0.72 |
| 40| 7588 | 98.27 | 54.27 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.53 | 7.30 | 0.41 |
| 2| 699 | 22.58 | 7.95 | 0.42 |
| 3| 830 | 24.09 | 9.05 | 0.45 |
| 5| 1316 | 31.92 | 12.58 | 0.56 |
| 10| 2143 | 44.06 | 19.29 | 0.74 |
| 41| 6584 | 98.46 | 55.08 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.47 | 8.46 | 0.46 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 1035 | 32.33 | 11.18 | 0.54 |
| 5| 1335 | 38.82 | 14.32 | 0.63 |
| 10| 1897 | 46.01 | 19.61 | 0.75 |
| 34| 5690 | 94.30 | 49.27 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 765 | 35.17 | 11.17 | 0.55 |
| 3| 895 | 37.20 | 12.40 | 0.58 |
| 5| 1238 | 42.60 | 15.27 | 0.66 |
| 10| 2072 | 54.17 | 21.85 | 0.84 |
| 30| 4919 | 99.03 | 47.62 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5937 | 35.77 | 12.01 | 0.79 |
| 3| 5971 | 40.46 | 13.49 | 0.84 |
| 4| 6141 | 49.69 | 16.62 | 0.94 |
| 5| 6285 | 58.71 | 19.71 | 1.04 |
| 6| 6543 | 70.63 | 23.78 | 1.18 |
| 7| 6547 | 77.81 | 26.10 | 1.26 |
| 8| 6934 | 92.08 | 31.01 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 40.58 | 14.82 | 0.86 |
| 10 | 20 | 1136 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 37 | 2106 | 7091 | 95.46 | 36.48 | 1.50 |

