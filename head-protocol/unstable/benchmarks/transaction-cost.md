--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-23 05:11:41.820170371 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.31 | 9.25 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.35 | 11.96 | 0.60 |
| 4 | 226 | 858 | 52.35 | 14.98 | 0.72 |
| 5 | 282 | 969 | 60.87 | 17.41 | 0.81 |
| 6 | 337 | 1081 | 76.01 | 21.55 | 0.97 |
| 7 | 394 | 1196 | 86.80 | 24.46 | 1.08 |
| 8 | 450 | 1303 | 98.79 | 27.73 | 1.21 |
| 9 | 507 | 1414 | 96.16 | 27.50 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1929 | 25.43 | 8.68 | 0.50 |
| 3| 2145 | 27.86 | 10.03 | 0.54 |
| 5| 2391 | 31.20 | 12.29 | 0.60 |
| 10| 3300 | 44.02 | 19.20 | 0.79 |
| 39| 7447 | 94.51 | 52.58 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.84 | 7.38 | 0.42 |
| 2| 821 | 25.36 | 8.75 | 0.45 |
| 3| 943 | 26.93 | 9.85 | 0.48 |
| 5| 1115 | 27.12 | 11.22 | 0.50 |
| 10| 2071 | 39.62 | 18.05 | 0.69 |
| 45| 6999 | 99.27 | 57.96 | 1.68 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 29.13 | 8.90 | 0.48 |
| 2| 857 | 31.58 | 10.26 | 0.52 |
| 3| 1000 | 31.58 | 10.95 | 0.53 |
| 5| 1241 | 37.02 | 13.78 | 0.60 |
| 10| 2016 | 44.63 | 19.30 | 0.74 |
| 38| 5943 | 97.32 | 52.67 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 849 | 36.56 | 11.60 | 0.57 |
| 3| 958 | 37.95 | 12.63 | 0.59 |
| 5| 1284 | 42.68 | 15.29 | 0.66 |
| 10| 2176 | 56.08 | 22.43 | 0.86 |
| 29| 4772 | 96.61 | 46.28 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.92 | 9.04 | 0.69 |
| 2| 5822 | 31.52 | 10.48 | 0.74 |
| 3| 6111 | 45.73 | 15.42 | 0.90 |
| 4| 6242 | 53.82 | 18.08 | 0.99 |
| 5| 6391 | 63.86 | 21.49 | 1.10 |
| 6| 6590 | 73.82 | 24.87 | 1.22 |
| 7| 6629 | 81.29 | 27.33 | 1.30 |
| 8| 6841 | 92.81 | 31.24 | 1.43 |
| 10| 6874 | 95.45 | 31.96 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 30.42 | 10.80 | 0.74 |
| 10 | 30 | 1708 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 40 | 2278 | 7195 | 99.66 | 38.24 | 1.55 |

