--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-12 04:33:50.056357958 UTC |
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
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 171 | 747 | 40.21 | 11.69 | 0.59 |
| 4 | 226 | 858 | 52.67 | 15.08 | 0.72 |
| 5 | 283 | 969 | 63.52 | 18.05 | 0.84 |
| 6 | 338 | 1081 | 66.25 | 19.06 | 0.87 |
| 7 | 394 | 1192 | 72.80 | 21.11 | 0.94 |
| 8 | 449 | 1303 | 80.96 | 23.51 | 1.03 |
| 9 | 505 | 1414 | 93.83 | 26.94 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.00 | 7.62 | 0.48 |
| 2| 1924 | 25.55 | 8.72 | 0.50 |
| 3| 2063 | 27.39 | 9.88 | 0.53 |
| 5| 2391 | 31.26 | 12.30 | 0.60 |
| 10| 3119 | 39.66 | 17.99 | 0.74 |
| 39| 7453 | 96.91 | 53.22 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 22.81 | 7.37 | 0.42 |
| 2| 776 | 24.28 | 8.45 | 0.44 |
| 3| 910 | 24.99 | 9.29 | 0.46 |
| 5| 1166 | 28.12 | 11.50 | 0.51 |
| 10| 1945 | 37.59 | 17.48 | 0.67 |
| 40| 6448 | 95.12 | 53.48 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 29.13 | 8.90 | 0.48 |
| 2| 826 | 31.58 | 10.26 | 0.52 |
| 3| 970 | 33.40 | 11.43 | 0.55 |
| 5| 1238 | 34.37 | 13.04 | 0.58 |
| 10| 2068 | 47.92 | 20.20 | 0.77 |
| 36| 5973 | 97.12 | 51.40 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 882 | 36.60 | 11.61 | 0.57 |
| 3| 952 | 37.91 | 12.62 | 0.59 |
| 5| 1360 | 44.07 | 15.71 | 0.68 |
| 10| 1978 | 53.39 | 21.60 | 0.82 |
| 30| 4960 | 99.33 | 47.74 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5798 | 26.97 | 9.05 | 0.69 |
| 2| 6006 | 36.97 | 12.45 | 0.80 |
| 3| 6019 | 43.88 | 14.71 | 0.88 |
| 4| 6282 | 55.20 | 18.59 | 1.01 |
| 5| 6365 | 60.34 | 20.28 | 1.06 |
| 6| 6482 | 71.75 | 24.10 | 1.19 |
| 7| 6821 | 84.43 | 28.51 | 1.34 |
| 8| 6924 | 94.59 | 32.00 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1136 | 6511 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7160 | 98.86 | 37.86 | 1.54 |

