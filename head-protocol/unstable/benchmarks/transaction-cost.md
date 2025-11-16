--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-16 04:36:25.832719803 UTC |
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
| 1| 5836 | 10.36 | 3.28 | 0.51 |
| 2| 6035 | 12.54 | 3.97 | 0.55 |
| 3| 6238 | 14.78 | 4.68 | 0.58 |
| 5| 6638 | 18.79 | 5.94 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 40.09 | 11.66 | 0.59 |
| 4 | 227 | 858 | 53.93 | 15.36 | 0.73 |
| 5 | 284 | 969 | 64.14 | 18.23 | 0.84 |
| 6 | 340 | 1085 | 65.76 | 19.01 | 0.87 |
| 7 | 394 | 1196 | 87.33 | 24.67 | 1.09 |
| 8 | 452 | 1303 | 91.77 | 25.99 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.37 | 7.71 | 0.48 |
| 2| 1922 | 25.51 | 8.70 | 0.50 |
| 3| 2053 | 27.39 | 9.88 | 0.53 |
| 5| 2388 | 31.03 | 12.25 | 0.59 |
| 10| 3070 | 38.84 | 17.75 | 0.73 |
| 40| 7484 | 96.43 | 53.77 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.80 | 7.37 | 0.42 |
| 2| 695 | 22.55 | 7.95 | 0.42 |
| 3| 1020 | 28.33 | 10.24 | 0.50 |
| 5| 1246 | 30.60 | 12.22 | 0.54 |
| 10| 2097 | 43.53 | 19.12 | 0.73 |
| 40| 6421 | 96.81 | 53.93 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.47 | 8.46 | 0.46 |
| 2| 823 | 31.66 | 10.29 | 0.52 |
| 3| 960 | 33.40 | 11.43 | 0.54 |
| 5| 1315 | 35.65 | 13.44 | 0.59 |
| 10| 1862 | 42.58 | 18.67 | 0.71 |
| 36| 6054 | 99.00 | 51.91 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.79 | 10.15 | 0.53 |
| 2| 806 | 35.81 | 11.37 | 0.56 |
| 3| 946 | 37.95 | 12.63 | 0.59 |
| 5| 1324 | 43.24 | 15.47 | 0.67 |
| 10| 1965 | 53.16 | 21.54 | 0.82 |
| 29| 4889 | 98.51 | 46.84 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5823 | 26.96 | 9.06 | 0.69 |
| 2| 5822 | 31.60 | 10.51 | 0.74 |
| 3| 6072 | 42.60 | 14.28 | 0.86 |
| 4| 6210 | 53.49 | 18.02 | 0.99 |
| 5| 6380 | 64.64 | 21.75 | 1.11 |
| 6| 6524 | 70.89 | 23.87 | 1.18 |
| 7| 6848 | 84.84 | 28.71 | 1.34 |
| 8| 6953 | 94.00 | 31.73 | 1.44 |
| 9| 7111 | 98.76 | 33.34 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2222 | 7162 | 98.05 | 37.58 | 1.53 |

