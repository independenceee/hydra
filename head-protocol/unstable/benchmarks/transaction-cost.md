--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-14 11:51:45.680855072 UTC |
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
| 1| 5837 | 10.85 | 3.45 | 0.52 |
| 2| 6041 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6638 | 18.91 | 5.98 | 0.64 |
| 10| 7647 | 28.88 | 9.10 | 0.79 |
| 43| 14283 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 747 | 43.75 | 12.55 | 0.63 |
| 4 | 228 | 858 | 49.68 | 14.34 | 0.69 |
| 5 | 283 | 969 | 62.09 | 17.68 | 0.82 |
| 6 | 340 | 1081 | 69.88 | 20.00 | 0.91 |
| 7 | 393 | 1192 | 73.22 | 21.25 | 0.95 |
| 8 | 449 | 1303 | 93.51 | 26.41 | 1.15 |
| 9 | 506 | 1414 | 94.14 | 27.07 | 1.17 |
| 10 | 560 | 1529 | 97.38 | 28.31 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.00 | 7.62 | 0.48 |
| 2| 1881 | 24.43 | 8.40 | 0.49 |
| 3| 2150 | 28.78 | 10.28 | 0.55 |
| 5| 2410 | 32.07 | 12.54 | 0.61 |
| 10| 3236 | 42.97 | 18.91 | 0.78 |
| 39| 7611 | 99.00 | 53.81 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.81 | 7.38 | 0.42 |
| 2| 766 | 24.27 | 8.46 | 0.44 |
| 3| 903 | 25.06 | 9.31 | 0.46 |
| 5| 1302 | 31.22 | 12.38 | 0.55 |
| 10| 1933 | 38.63 | 17.80 | 0.68 |
| 42| 6731 | 99.85 | 56.14 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.17 | 8.91 | 0.48 |
| 2| 783 | 30.87 | 10.05 | 0.51 |
| 3| 939 | 32.76 | 11.24 | 0.54 |
| 5| 1315 | 37.70 | 13.98 | 0.61 |
| 10| 1990 | 47.36 | 20.02 | 0.76 |
| 34| 5826 | 96.26 | 49.86 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 33.87 | 10.16 | 0.53 |
| 2| 869 | 36.56 | 11.60 | 0.57 |
| 3| 954 | 37.84 | 12.60 | 0.59 |
| 5| 1248 | 42.68 | 15.29 | 0.66 |
| 10| 1999 | 53.41 | 21.61 | 0.83 |
| 30| 4989 | 99.58 | 47.82 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.13 | 9.11 | 0.69 |
| 2| 6000 | 36.89 | 12.43 | 0.80 |
| 3| 6156 | 46.00 | 15.51 | 0.90 |
| 4| 6231 | 54.97 | 18.54 | 1.00 |
| 5| 6328 | 56.66 | 18.97 | 1.02 |
| 6| 6608 | 73.26 | 24.68 | 1.21 |
| 7| 6790 | 83.93 | 28.29 | 1.33 |
| 8| 6700 | 91.40 | 30.71 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 10 | 570 | 6174 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1137 | 6511 | 58.66 | 22.07 | 1.07 |
| 10 | 39 | 2216 | 7156 | 98.68 | 37.80 | 1.53 |

