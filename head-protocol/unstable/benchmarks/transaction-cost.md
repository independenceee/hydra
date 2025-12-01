--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-01 05:01:25.448261724 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6242 | 14.38 | 4.54 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.38 | 9.27 | 0.79 |
| 43| 14279 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10037 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 170 | 747 | 40.18 | 11.66 | 0.59 |
| 4 | 227 | 862 | 53.76 | 15.32 | 0.73 |
| 5 | 283 | 969 | 55.92 | 16.23 | 0.76 |
| 6 | 338 | 1081 | 71.89 | 20.45 | 0.93 |
| 7 | 393 | 1192 | 76.63 | 21.98 | 0.98 |
| 8 | 448 | 1303 | 98.21 | 27.59 | 1.20 |
| 9 | 504 | 1414 | 96.92 | 27.68 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 24.00 | 7.62 | 0.48 |
| 2| 1925 | 25.92 | 8.80 | 0.51 |
| 3| 2118 | 28.31 | 10.14 | 0.55 |
| 5| 2407 | 32.15 | 12.56 | 0.61 |
| 10| 3069 | 40.03 | 18.08 | 0.74 |
| 41| 7623 | 96.04 | 54.33 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.84 | 7.37 | 0.41 |
| 2| 699 | 22.58 | 7.96 | 0.42 |
| 3| 1038 | 28.04 | 10.17 | 0.50 |
| 5| 1229 | 31.33 | 12.41 | 0.55 |
| 10| 1936 | 37.57 | 17.48 | 0.67 |
| 42| 6672 | 96.88 | 55.30 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.13 | 8.90 | 0.48 |
| 2| 873 | 29.97 | 9.84 | 0.50 |
| 3| 948 | 30.94 | 10.75 | 0.52 |
| 5| 1305 | 35.05 | 13.25 | 0.59 |
| 10| 2036 | 47.59 | 20.09 | 0.77 |
| 38| 6167 | 99.72 | 53.41 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.85 | 11.38 | 0.56 |
| 3| 966 | 37.91 | 12.62 | 0.59 |
| 5| 1317 | 43.25 | 15.47 | 0.67 |
| 10| 1953 | 53.45 | 21.62 | 0.82 |
| 29| 4869 | 98.32 | 46.77 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.00 | 9.07 | 0.69 |
| 2| 5936 | 35.88 | 12.04 | 0.79 |
| 3| 6064 | 43.60 | 14.61 | 0.87 |
| 4| 6345 | 55.08 | 18.66 | 1.01 |
| 5| 6451 | 65.24 | 21.97 | 1.12 |
| 6| 6629 | 70.97 | 23.86 | 1.19 |
| 7| 6753 | 84.74 | 28.57 | 1.34 |
| 8| 7019 | 95.86 | 32.40 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 30 | 1708 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2274 | 7190 | 99.66 | 38.24 | 1.55 |

