--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-11 04:46:06.943003773 UTC |
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
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6646 | 19.10 | 6.05 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 751 | 40.05 | 11.65 | 0.59 |
| 4 | 225 | 858 | 47.82 | 13.92 | 0.67 |
| 5 | 282 | 969 | 63.26 | 18.05 | 0.83 |
| 6 | 340 | 1085 | 69.93 | 19.98 | 0.91 |
| 7 | 396 | 1192 | 82.30 | 23.33 | 1.04 |
| 8 | 450 | 1303 | 98.95 | 27.81 | 1.21 |
| 9 | 505 | 1414 | 89.92 | 26.17 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1954 | 25.85 | 8.78 | 0.51 |
| 3| 2074 | 27.32 | 9.89 | 0.53 |
| 5| 2275 | 28.82 | 11.63 | 0.57 |
| 10| 3070 | 40.16 | 18.11 | 0.74 |
| 42| 7737 | 96.06 | 54.99 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.84 | 7.38 | 0.41 |
| 2| 769 | 24.35 | 8.47 | 0.44 |
| 3| 874 | 25.82 | 9.54 | 0.47 |
| 5| 1275 | 29.96 | 12.02 | 0.54 |
| 10| 2112 | 41.56 | 18.61 | 0.71 |
| 40| 6485 | 98.83 | 54.51 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 27.50 | 8.46 | 0.46 |
| 2| 865 | 29.97 | 9.84 | 0.50 |
| 3| 971 | 33.40 | 11.44 | 0.55 |
| 5| 1265 | 35.01 | 13.24 | 0.58 |
| 10| 2036 | 47.70 | 20.12 | 0.77 |
| 37| 6146 | 98.76 | 52.51 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 825 | 35.92 | 11.40 | 0.56 |
| 3| 980 | 38.47 | 12.79 | 0.60 |
| 5| 1302 | 43.13 | 15.44 | 0.67 |
| 10| 2030 | 53.86 | 21.76 | 0.83 |
| 29| 4929 | 98.95 | 47.02 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 27.13 | 9.10 | 0.69 |
| 2| 5991 | 36.88 | 12.44 | 0.80 |
| 3| 6083 | 42.53 | 14.29 | 0.86 |
| 4| 6279 | 55.20 | 18.59 | 1.01 |
| 5| 6435 | 65.47 | 22.10 | 1.12 |
| 6| 6549 | 74.20 | 25.02 | 1.22 |
| 7| 6722 | 81.93 | 27.58 | 1.31 |
| 8| 6770 | 88.46 | 29.73 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 30 | 1709 | 6856 | 78.71 | 30.00 | 1.30 |
| 10 | 39 | 2220 | 7160 | 99.05 | 37.93 | 1.54 |

