--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-05 04:39:56.854668862 UTC |
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
| 1| 5841 | 10.40 | 3.30 | 0.52 |
| 2| 6038 | 12.54 | 3.97 | 0.55 |
| 3| 6238 | 14.88 | 4.72 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7651 | 29.14 | 9.19 | 0.79 |
| 43| 14285 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 43.51 | 12.45 | 0.62 |
| 4 | 225 | 858 | 53.32 | 15.21 | 0.73 |
| 5 | 282 | 969 | 63.97 | 18.13 | 0.84 |
| 6 | 340 | 1081 | 71.83 | 20.51 | 0.93 |
| 7 | 394 | 1192 | 79.53 | 22.85 | 1.01 |
| 8 | 450 | 1303 | 91.49 | 25.93 | 1.13 |
| 9 | 505 | 1414 | 96.73 | 27.69 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.00 | 7.62 | 0.48 |
| 2| 1941 | 25.92 | 8.80 | 0.51 |
| 3| 2116 | 28.31 | 10.14 | 0.55 |
| 5| 2477 | 33.43 | 12.91 | 0.62 |
| 10| 3184 | 41.51 | 18.51 | 0.76 |
| 41| 7514 | 95.62 | 54.23 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.57 | 7.31 | 0.41 |
| 2| 808 | 25.10 | 8.68 | 0.45 |
| 3| 1036 | 28.12 | 10.19 | 0.50 |
| 5| 1280 | 31.29 | 12.40 | 0.55 |
| 10| 2027 | 39.11 | 17.91 | 0.68 |
| 42| 6728 | 98.50 | 55.80 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 27.54 | 8.47 | 0.46 |
| 2| 835 | 29.15 | 9.59 | 0.49 |
| 3| 965 | 30.82 | 10.73 | 0.52 |
| 5| 1215 | 36.90 | 13.75 | 0.60 |
| 10| 1979 | 44.04 | 19.11 | 0.73 |
| 36| 6075 | 99.07 | 51.95 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 882 | 36.56 | 11.60 | 0.57 |
| 3| 1029 | 38.58 | 12.82 | 0.60 |
| 5| 1308 | 43.36 | 15.49 | 0.67 |
| 10| 2006 | 53.68 | 21.69 | 0.83 |
| 30| 4926 | 97.97 | 47.32 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5914 | 36.01 | 12.09 | 0.79 |
| 3| 6138 | 45.78 | 15.44 | 0.90 |
| 4| 6362 | 56.91 | 19.25 | 1.03 |
| 5| 6318 | 60.02 | 20.19 | 1.06 |
| 6| 6318 | 64.29 | 21.48 | 1.10 |
| 7| 6628 | 76.83 | 25.88 | 1.25 |
| 8| 6612 | 79.21 | 26.47 | 1.27 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 30 | 1709 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2165 | 7128 | 96.63 | 36.99 | 1.51 |

