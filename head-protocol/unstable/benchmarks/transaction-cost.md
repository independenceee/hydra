--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-09 04:32:30.215640393 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.34 | 3.90 | 0.54 |
| 3| 6236 | 14.98 | 4.75 | 0.58 |
| 5| 6638 | 18.93 | 5.98 | 0.64 |
| 10| 7650 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.08 | 11.87 | 0.60 |
| 4 | 226 | 858 | 49.35 | 14.24 | 0.69 |
| 5 | 281 | 969 | 62.62 | 17.83 | 0.83 |
| 6 | 342 | 1081 | 69.29 | 19.82 | 0.90 |
| 7 | 395 | 1192 | 78.43 | 22.45 | 1.00 |
| 8 | 448 | 1303 | 91.95 | 26.13 | 1.14 |
| 10 | 560 | 1525 | 97.56 | 28.18 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1924 | 25.88 | 8.79 | 0.51 |
| 3| 2112 | 28.10 | 10.09 | 0.54 |
| 5| 2360 | 31.37 | 12.33 | 0.60 |
| 10| 3251 | 42.24 | 18.71 | 0.77 |
| 41| 7665 | 97.80 | 54.81 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.80 | 7.37 | 0.41 |
| 2| 808 | 25.41 | 8.76 | 0.45 |
| 3| 930 | 26.86 | 9.84 | 0.48 |
| 5| 1333 | 32.35 | 12.69 | 0.56 |
| 10| 2114 | 42.75 | 18.94 | 0.73 |
| 39| 6256 | 91.02 | 51.70 | 1.53 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 27.47 | 8.46 | 0.46 |
| 2| 845 | 29.22 | 9.61 | 0.49 |
| 3| 935 | 32.72 | 11.23 | 0.54 |
| 5| 1130 | 35.56 | 13.33 | 0.58 |
| 10| 2076 | 48.87 | 20.47 | 0.78 |
| 36| 5861 | 95.33 | 50.86 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 33.83 | 10.16 | 0.53 |
| 2| 828 | 35.88 | 11.39 | 0.56 |
| 3| 939 | 37.84 | 12.60 | 0.59 |
| 5| 1300 | 42.64 | 15.28 | 0.66 |
| 10| 2110 | 55.67 | 22.30 | 0.85 |
| 29| 4987 | 99.57 | 47.14 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5780 | 27.16 | 9.10 | 0.69 |
| 2| 5917 | 34.75 | 11.63 | 0.78 |
| 3| 6124 | 45.42 | 15.34 | 0.90 |
| 4| 6120 | 52.67 | 17.67 | 0.97 |
| 5| 6283 | 59.48 | 19.91 | 1.05 |
| 6| 6701 | 75.68 | 25.55 | 1.24 |
| 7| 6584 | 75.22 | 25.23 | 1.23 |
| 8| 6910 | 94.47 | 31.87 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 30 | 1707 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.49 | 37.73 | 1.53 |

