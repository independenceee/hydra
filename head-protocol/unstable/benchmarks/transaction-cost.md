--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-15 04:15:40.345918947 UTC |
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
| 2| 6041 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.40 | 4.55 | 0.57 |
| 5| 6640 | 19.02 | 6.02 | 0.64 |
| 10| 7648 | 29.09 | 9.17 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 745 | 40.04 | 11.66 | 0.59 |
| 4 | 225 | 858 | 49.65 | 14.34 | 0.69 |
| 5 | 282 | 969 | 56.68 | 16.48 | 0.77 |
| 6 | 340 | 1081 | 67.16 | 19.31 | 0.88 |
| 7 | 394 | 1192 | 86.84 | 24.46 | 1.08 |
| 8 | 449 | 1303 | 93.50 | 26.45 | 1.15 |
| 9 | 506 | 1414 | 95.81 | 27.52 | 1.18 |
| 10 | 560 | 1525 | 99.70 | 28.62 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1880 | 24.43 | 8.40 | 0.49 |
| 3| 2097 | 28.38 | 10.16 | 0.55 |
| 5| 2406 | 30.91 | 12.22 | 0.59 |
| 10| 3150 | 40.69 | 18.28 | 0.75 |
| 40| 7555 | 97.48 | 54.06 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 22.81 | 7.37 | 0.42 |
| 2| 772 | 24.04 | 8.41 | 0.44 |
| 3| 904 | 25.05 | 9.32 | 0.46 |
| 5| 1205 | 29.67 | 11.96 | 0.53 |
| 10| 1864 | 36.40 | 17.15 | 0.65 |
| 42| 6819 | 99.63 | 56.10 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 831 | 29.22 | 9.61 | 0.49 |
| 3| 1016 | 34.10 | 11.65 | 0.55 |
| 5| 1309 | 35.61 | 13.43 | 0.59 |
| 10| 2076 | 45.65 | 19.59 | 0.75 |
| 34| 5824 | 96.17 | 49.81 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 830 | 35.89 | 11.39 | 0.56 |
| 3| 891 | 37.24 | 12.41 | 0.58 |
| 5| 1261 | 42.49 | 15.24 | 0.66 |
| 10| 2199 | 56.27 | 22.47 | 0.86 |
| 29| 4757 | 96.57 | 46.29 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.09 | 9.09 | 0.69 |
| 2| 5917 | 34.90 | 11.68 | 0.78 |
| 3| 6061 | 42.44 | 14.27 | 0.86 |
| 4| 6301 | 54.81 | 18.46 | 1.00 |
| 5| 6312 | 60.28 | 20.33 | 1.06 |
| 6| 6533 | 73.28 | 24.63 | 1.21 |
| 7| 6564 | 77.93 | 26.14 | 1.26 |
| 8| 6841 | 91.70 | 30.85 | 1.41 |
| 9| 6934 | 97.74 | 32.86 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1703 | 6849 | 80.22 | 30.52 | 1.32 |
| 10 | 37 | 2106 | 7091 | 94.39 | 36.12 | 1.49 |

