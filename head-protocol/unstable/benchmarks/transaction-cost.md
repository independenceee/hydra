--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-02 04:14:34.944163086 UTC |
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
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6643 | 18.88 | 5.97 | 0.64 |
| 10| 7644 | 29.49 | 9.31 | 0.79 |
| 43| 14281 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.35 | 9.42 | 0.51 |
| 3 | 170 | 751 | 41.24 | 11.91 | 0.60 |
| 4 | 227 | 858 | 50.03 | 14.50 | 0.70 |
| 5 | 284 | 969 | 56.33 | 16.39 | 0.77 |
| 6 | 337 | 1081 | 73.69 | 20.91 | 0.94 |
| 7 | 394 | 1192 | 75.59 | 21.90 | 0.97 |
| 8 | 449 | 1303 | 87.72 | 25.08 | 1.10 |
| 9 | 504 | 1418 | 88.53 | 25.67 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 24.00 | 7.62 | 0.48 |
| 2| 1931 | 25.39 | 8.68 | 0.50 |
| 3| 2059 | 27.35 | 9.87 | 0.53 |
| 5| 2534 | 34.27 | 13.15 | 0.63 |
| 10| 3168 | 40.92 | 18.33 | 0.75 |
| 39| 7391 | 94.71 | 52.61 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.38 | 0.41 |
| 2| 818 | 25.55 | 8.81 | 0.46 |
| 3| 935 | 26.20 | 9.64 | 0.47 |
| 5| 1143 | 28.11 | 11.51 | 0.51 |
| 10| 1895 | 37.64 | 17.49 | 0.66 |
| 42| 6643 | 96.23 | 55.12 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 660 | 29.17 | 8.91 | 0.48 |
| 2| 834 | 31.58 | 10.26 | 0.52 |
| 3| 1041 | 31.61 | 10.96 | 0.53 |
| 5| 1337 | 35.79 | 13.48 | 0.60 |
| 10| 2055 | 45.80 | 19.63 | 0.75 |
| 37| 6049 | 99.19 | 52.63 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.83 | 10.15 | 0.53 |
| 2| 835 | 35.88 | 11.39 | 0.56 |
| 3| 1035 | 38.63 | 12.83 | 0.60 |
| 5| 1209 | 41.82 | 15.03 | 0.65 |
| 10| 2016 | 54.10 | 21.82 | 0.83 |
| 28| 4851 | 97.23 | 45.84 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 27.08 | 9.08 | 0.69 |
| 2| 5822 | 31.63 | 10.53 | 0.74 |
| 3| 6095 | 45.77 | 15.44 | 0.90 |
| 4| 6381 | 56.53 | 19.12 | 1.03 |
| 5| 6250 | 56.33 | 18.84 | 1.02 |
| 6| 6347 | 61.24 | 20.48 | 1.07 |
| 7| 6821 | 85.27 | 28.85 | 1.35 |
| 8| 6794 | 88.15 | 29.61 | 1.37 |
| 9| 6706 | 86.40 | 28.88 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 58.66 | 22.07 | 1.07 |
| 10 | 39 | 2221 | 7161 | 99.38 | 38.04 | 1.54 |

