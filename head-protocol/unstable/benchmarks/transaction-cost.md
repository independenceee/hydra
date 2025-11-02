--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-02 04:27:08.519044526 UTC |
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
| 1| 5840 | 10.26 | 3.25 | 0.51 |
| 2| 6038 | 12.41 | 3.92 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 924 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 40.00 | 11.63 | 0.59 |
| 4 | 226 | 858 | 52.64 | 15.08 | 0.72 |
| 5 | 284 | 969 | 56.47 | 16.36 | 0.77 |
| 6 | 339 | 1081 | 68.38 | 19.65 | 0.89 |
| 7 | 396 | 1196 | 82.45 | 23.37 | 1.04 |
| 8 | 449 | 1303 | 87.25 | 24.91 | 1.09 |
| 9 | 506 | 1414 | 91.93 | 26.54 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1924 | 25.76 | 8.76 | 0.51 |
| 3| 2055 | 27.35 | 9.87 | 0.53 |
| 5| 2359 | 31.48 | 12.36 | 0.60 |
| 10| 3186 | 41.73 | 18.57 | 0.76 |
| 40| 7617 | 97.57 | 54.09 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.84 | 7.37 | 0.42 |
| 2| 695 | 22.55 | 7.94 | 0.42 |
| 3| 965 | 26.67 | 9.79 | 0.48 |
| 5| 1219 | 29.06 | 11.78 | 0.52 |
| 10| 1956 | 38.50 | 17.75 | 0.68 |
| 41| 6716 | 99.27 | 55.31 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 27.50 | 8.46 | 0.46 |
| 2| 836 | 29.26 | 9.62 | 0.49 |
| 3| 983 | 33.47 | 11.46 | 0.55 |
| 5| 1179 | 36.39 | 13.58 | 0.59 |
| 10| 2171 | 48.79 | 20.46 | 0.79 |
| 37| 5817 | 95.71 | 51.56 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 820 | 35.92 | 11.40 | 0.56 |
| 3| 1056 | 39.27 | 13.03 | 0.61 |
| 5| 1311 | 43.28 | 15.48 | 0.67 |
| 10| 1940 | 53.24 | 21.56 | 0.82 |
| 29| 4757 | 97.24 | 46.44 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5783 | 27.13 | 9.09 | 0.69 |
| 2| 5912 | 36.07 | 12.11 | 0.79 |
| 3| 6127 | 45.73 | 15.42 | 0.90 |
| 4| 6256 | 55.41 | 18.66 | 1.01 |
| 5| 6290 | 62.06 | 20.80 | 1.08 |
| 6| 6551 | 73.21 | 24.66 | 1.21 |
| 7| 6634 | 80.23 | 26.87 | 1.28 |
| 8| 7041 | 94.80 | 31.99 | 1.46 |
| 9| 6825 | 91.41 | 30.68 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.21 | 10.04 | 0.71 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2221 | 7161 | 97.61 | 37.43 | 1.52 |

