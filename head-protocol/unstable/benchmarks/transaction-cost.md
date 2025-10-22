--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-22 05:21:50.36630303 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.54 | 3.97 | 0.55 |
| 3| 6239 | 14.38 | 4.54 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10046 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.38 | 9.91 | 0.53 |
| 3 | 171 | 747 | 41.01 | 11.85 | 0.60 |
| 4 | 227 | 858 | 51.00 | 14.69 | 0.71 |
| 5 | 283 | 974 | 61.51 | 17.63 | 0.82 |
| 6 | 339 | 1081 | 66.52 | 19.20 | 0.87 |
| 7 | 394 | 1192 | 76.71 | 22.04 | 0.98 |
| 8 | 448 | 1307 | 94.28 | 26.65 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.29 | 7.69 | 0.48 |
| 2| 1883 | 24.40 | 8.39 | 0.49 |
| 3| 2128 | 28.31 | 10.14 | 0.55 |
| 5| 2402 | 31.91 | 12.48 | 0.60 |
| 10| 3134 | 41.01 | 18.35 | 0.75 |
| 39| 7385 | 95.09 | 52.70 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.38 | 0.41 |
| 2| 741 | 23.66 | 8.26 | 0.43 |
| 3| 941 | 27.08 | 9.89 | 0.48 |
| 5| 1302 | 30.04 | 12.04 | 0.54 |
| 10| 2134 | 43.44 | 19.11 | 0.73 |
| 41| 6700 | 98.11 | 54.98 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.17 | 8.91 | 0.48 |
| 2| 778 | 30.98 | 10.08 | 0.51 |
| 3| 1013 | 31.61 | 10.96 | 0.53 |
| 5| 1247 | 37.13 | 13.80 | 0.60 |
| 10| 1870 | 45.87 | 19.57 | 0.74 |
| 37| 6082 | 98.45 | 52.43 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 806 | 35.92 | 11.40 | 0.56 |
| 3| 1025 | 38.66 | 12.84 | 0.60 |
| 5| 1196 | 42.01 | 15.08 | 0.65 |
| 10| 1903 | 52.79 | 21.41 | 0.81 |
| 30| 4992 | 99.40 | 47.74 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5807 | 26.97 | 9.05 | 0.69 |
| 2| 5868 | 35.02 | 11.73 | 0.78 |
| 3| 6074 | 44.92 | 15.09 | 0.89 |
| 4| 6199 | 54.06 | 18.18 | 0.99 |
| 5| 6360 | 60.38 | 20.34 | 1.06 |
| 6| 6602 | 73.51 | 24.74 | 1.21 |
| 7| 6464 | 71.85 | 24.06 | 1.19 |
| 8| 6983 | 95.09 | 32.12 | 1.46 |
| 9| 6954 | 98.04 | 32.93 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 568 | 6172 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.28 | 22.29 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2163 | 7125 | 97.07 | 37.14 | 1.52 |

