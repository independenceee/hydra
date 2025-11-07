--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-07 04:32:46.003857183 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7650 | 29.09 | 9.17 | 0.79 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 32.31 | 9.40 | 0.51 |
| 3 | 171 | 747 | 41.24 | 11.91 | 0.60 |
| 4 | 227 | 858 | 49.96 | 14.46 | 0.70 |
| 5 | 282 | 969 | 59.44 | 17.10 | 0.80 |
| 6 | 338 | 1081 | 67.58 | 19.45 | 0.88 |
| 7 | 394 | 1196 | 85.20 | 24.16 | 1.07 |
| 8 | 451 | 1303 | 80.85 | 23.43 | 1.03 |
| 9 | 505 | 1414 | 88.50 | 25.71 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2146 | 29.01 | 10.35 | 0.55 |
| 5| 2363 | 31.48 | 12.36 | 0.60 |
| 10| 3202 | 42.22 | 18.69 | 0.77 |
| 40| 7631 | 96.80 | 53.88 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 611 | 22.57 | 7.31 | 0.41 |
| 2| 832 | 25.53 | 8.79 | 0.46 |
| 3| 828 | 24.02 | 9.01 | 0.45 |
| 5| 1257 | 31.08 | 12.34 | 0.55 |
| 10| 1954 | 37.32 | 17.41 | 0.66 |
| 41| 6647 | 99.72 | 55.42 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 27.50 | 8.46 | 0.46 |
| 2| 878 | 29.86 | 9.81 | 0.50 |
| 3| 1081 | 32.36 | 11.19 | 0.54 |
| 5| 1231 | 34.29 | 13.02 | 0.58 |
| 10| 1933 | 43.59 | 18.96 | 0.72 |
| 35| 5706 | 99.49 | 51.24 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 870 | 36.48 | 11.58 | 0.57 |
| 3| 947 | 37.87 | 12.61 | 0.59 |
| 5| 1263 | 42.53 | 15.25 | 0.66 |
| 10| 2092 | 54.99 | 22.10 | 0.85 |
| 28| 4868 | 96.29 | 45.60 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.13 | 9.09 | 0.69 |
| 2| 5912 | 35.95 | 12.07 | 0.79 |
| 3| 5971 | 40.28 | 13.43 | 0.84 |
| 4| 6164 | 53.21 | 17.84 | 0.98 |
| 5| 6196 | 55.15 | 18.39 | 1.00 |
| 6| 6785 | 75.79 | 25.70 | 1.25 |
| 7| 6657 | 82.37 | 27.79 | 1.31 |
| 8| 6780 | 89.74 | 30.27 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 571 | 6176 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 38 | 2165 | 7128 | 96.88 | 37.08 | 1.51 |

