--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-13 04:51:10.181945384 UTC |
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
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.47 | 4.57 | 0.57 |
| 5| 6640 | 18.60 | 5.87 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 913 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 227 | 858 | 49.58 | 14.29 | 0.69 |
| 5 | 282 | 969 | 59.31 | 17.04 | 0.79 |
| 6 | 338 | 1081 | 63.73 | 18.49 | 0.85 |
| 7 | 396 | 1192 | 77.55 | 22.15 | 0.99 |
| 8 | 451 | 1303 | 82.83 | 23.95 | 1.05 |
| 9 | 504 | 1414 | 91.77 | 26.40 | 1.14 |
| 10 | 561 | 1529 | 99.11 | 28.60 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 1936 | 25.47 | 8.70 | 0.50 |
| 3| 2013 | 25.98 | 9.50 | 0.52 |
| 5| 2326 | 30.37 | 12.05 | 0.58 |
| 10| 3200 | 41.96 | 18.62 | 0.76 |
| 38| 7159 | 91.49 | 51.06 | 1.57 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.81 | 7.37 | 0.42 |
| 2| 741 | 23.58 | 8.22 | 0.43 |
| 3| 902 | 25.09 | 9.33 | 0.46 |
| 5| 1172 | 28.66 | 11.68 | 0.52 |
| 10| 1998 | 39.90 | 18.13 | 0.69 |
| 43| 6746 | 97.40 | 56.14 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 29.13 | 8.90 | 0.48 |
| 2| 814 | 29.22 | 9.61 | 0.49 |
| 3| 864 | 32.09 | 11.03 | 0.53 |
| 5| 1334 | 35.69 | 13.45 | 0.59 |
| 10| 2048 | 47.93 | 20.20 | 0.77 |
| 34| 5657 | 98.88 | 50.46 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 822 | 35.89 | 11.39 | 0.56 |
| 3| 989 | 38.63 | 12.83 | 0.60 |
| 5| 1275 | 42.53 | 15.25 | 0.66 |
| 10| 2127 | 55.43 | 22.24 | 0.85 |
| 29| 4778 | 97.24 | 46.48 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5834 | 27.08 | 9.09 | 0.69 |
| 2| 5935 | 35.89 | 12.04 | 0.79 |
| 3| 6202 | 46.81 | 15.84 | 0.92 |
| 4| 6237 | 54.88 | 18.47 | 1.00 |
| 5| 6286 | 59.49 | 19.96 | 1.05 |
| 6| 6631 | 75.31 | 25.43 | 1.23 |
| 7| 6684 | 79.95 | 27.00 | 1.28 |
| 8| 6921 | 93.11 | 31.40 | 1.43 |
| 9| 7013 | 99.15 | 33.33 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 285 | 6005 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 567 | 6171 | 37.74 | 13.85 | 0.83 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2281 | 7198 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2218 | 7157 | 98.05 | 37.58 | 1.53 |

