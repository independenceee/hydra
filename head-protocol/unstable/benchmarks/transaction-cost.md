--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-28 04:32:52.883626281 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6042 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.78 | 4.68 | 0.58 |
| 5| 6638 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14286 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.96 | 12.60 | 0.63 |
| 4 | 226 | 858 | 52.33 | 14.95 | 0.72 |
| 5 | 283 | 974 | 57.60 | 16.66 | 0.78 |
| 6 | 337 | 1081 | 73.96 | 21.02 | 0.95 |
| 7 | 395 | 1192 | 74.72 | 21.56 | 0.96 |
| 8 | 448 | 1303 | 85.12 | 24.45 | 1.07 |
| 9 | 504 | 1414 | 98.51 | 27.95 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.77 | 8.48 | 0.49 |
| 3| 2060 | 26.99 | 9.78 | 0.53 |
| 5| 2404 | 32.15 | 12.56 | 0.61 |
| 10| 3127 | 40.62 | 18.26 | 0.75 |
| 39| 7704 | 99.42 | 53.93 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.80 | 7.38 | 0.41 |
| 2| 807 | 25.55 | 8.79 | 0.46 |
| 3| 876 | 25.78 | 9.53 | 0.47 |
| 5| 1380 | 31.96 | 12.60 | 0.56 |
| 10| 2027 | 40.32 | 18.25 | 0.70 |
| 42| 6749 | 99.90 | 56.15 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.42 | 8.68 | 0.47 |
| 2| 881 | 31.66 | 10.28 | 0.52 |
| 3| 935 | 32.76 | 11.24 | 0.54 |
| 5| 1262 | 35.01 | 13.24 | 0.58 |
| 10| 2119 | 45.52 | 19.56 | 0.75 |
| 37| 6087 | 99.50 | 52.70 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.17 | 11.17 | 0.55 |
| 3| 937 | 37.95 | 12.63 | 0.59 |
| 5| 1274 | 42.57 | 15.26 | 0.66 |
| 10| 2055 | 54.96 | 22.07 | 0.84 |
| 29| 4978 | 98.18 | 46.79 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 27.13 | 9.09 | 0.69 |
| 2| 5959 | 37.09 | 12.52 | 0.80 |
| 3| 6190 | 46.20 | 15.59 | 0.91 |
| 4| 6139 | 50.16 | 16.81 | 0.95 |
| 5| 6425 | 63.75 | 21.52 | 1.10 |
| 6| 6504 | 73.00 | 24.67 | 1.20 |
| 7| 6714 | 83.70 | 28.18 | 1.33 |
| 8| 6846 | 90.26 | 30.40 | 1.40 |
| 9| 6953 | 95.03 | 31.92 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 284 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2276 | 7192 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2222 | 7161 | 99.38 | 38.04 | 1.54 |

