--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-30 04:49:55.574630053 UTC |
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
| 1| 5837 | 10.28 | 3.25 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7651 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 43.81 | 12.53 | 0.63 |
| 4 | 228 | 858 | 47.98 | 13.94 | 0.68 |
| 5 | 283 | 969 | 59.40 | 17.09 | 0.80 |
| 6 | 340 | 1081 | 65.77 | 19.01 | 0.87 |
| 7 | 394 | 1192 | 83.14 | 23.67 | 1.05 |
| 8 | 450 | 1303 | 87.47 | 25.06 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1783 | 24.00 | 7.62 | 0.48 |
| 2| 1947 | 25.85 | 8.78 | 0.51 |
| 3| 2115 | 27.89 | 10.04 | 0.54 |
| 5| 2527 | 34.56 | 13.22 | 0.64 |
| 10| 3266 | 43.77 | 19.12 | 0.79 |
| 41| 7713 | 98.02 | 54.89 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.32 | 0.41 |
| 2| 811 | 25.53 | 8.79 | 0.46 |
| 3| 943 | 26.92 | 9.85 | 0.48 |
| 5| 1290 | 32.18 | 12.66 | 0.56 |
| 10| 2064 | 40.36 | 18.28 | 0.70 |
| 39| 6451 | 97.82 | 53.60 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 649 | 29.17 | 8.91 | 0.48 |
| 2| 815 | 29.26 | 9.62 | 0.49 |
| 3| 985 | 33.43 | 11.44 | 0.55 |
| 5| 1313 | 35.94 | 13.53 | 0.60 |
| 10| 2049 | 47.84 | 20.18 | 0.77 |
| 35| 5807 | 99.76 | 51.38 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 33.83 | 10.15 | 0.53 |
| 2| 804 | 35.89 | 11.39 | 0.56 |
| 3| 1003 | 38.62 | 12.83 | 0.60 |
| 5| 1157 | 41.29 | 14.86 | 0.64 |
| 10| 1978 | 53.24 | 21.56 | 0.82 |
| 28| 4807 | 95.63 | 45.38 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5840 | 27.05 | 9.08 | 0.69 |
| 2| 5959 | 35.76 | 12.01 | 0.79 |
| 3| 6153 | 45.70 | 15.40 | 0.90 |
| 4| 6303 | 56.34 | 19.01 | 1.02 |
| 5| 6417 | 64.09 | 21.59 | 1.11 |
| 6| 6461 | 68.59 | 23.02 | 1.15 |
| 7| 6513 | 75.17 | 25.17 | 1.23 |
| 8| 6910 | 95.03 | 32.16 | 1.45 |
| 9| 6934 | 98.78 | 33.22 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 568 | 6173 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1705 | 6851 | 78.27 | 29.85 | 1.30 |
| 10 | 40 | 2274 | 7190 | 99.22 | 38.09 | 1.54 |

