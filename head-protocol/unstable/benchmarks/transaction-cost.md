--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-21 05:11:55.502818207 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 15.14 | 4.81 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 640 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 747 | 41.47 | 11.99 | 0.60 |
| 4 | 225 | 858 | 47.52 | 13.80 | 0.67 |
| 5 | 283 | 969 | 57.86 | 16.73 | 0.78 |
| 6 | 337 | 1085 | 75.14 | 21.19 | 0.96 |
| 7 | 393 | 1192 | 82.47 | 23.37 | 1.04 |
| 8 | 451 | 1303 | 94.47 | 26.74 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 23.92 | 7.60 | 0.48 |
| 2| 1947 | 25.47 | 8.69 | 0.50 |
| 3| 2013 | 26.40 | 9.60 | 0.52 |
| 5| 2276 | 28.97 | 11.67 | 0.57 |
| 10| 3193 | 41.59 | 18.53 | 0.76 |
| 41| 7722 | 99.57 | 55.28 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 615 | 22.84 | 7.39 | 0.42 |
| 2| 772 | 23.56 | 8.22 | 0.43 |
| 3| 830 | 24.09 | 9.04 | 0.45 |
| 5| 1307 | 30.72 | 12.26 | 0.54 |
| 10| 1947 | 38.15 | 17.66 | 0.67 |
| 41| 6669 | 99.46 | 55.40 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 712 | 27.54 | 8.47 | 0.47 |
| 2| 778 | 30.91 | 10.06 | 0.51 |
| 3| 902 | 30.23 | 10.54 | 0.51 |
| 5| 1291 | 37.91 | 14.06 | 0.61 |
| 10| 2062 | 48.30 | 20.29 | 0.78 |
| 33| 5658 | 94.09 | 48.54 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.15 | 0.53 |
| 2| 812 | 35.85 | 11.38 | 0.56 |
| 3| 967 | 37.88 | 12.61 | 0.59 |
| 5| 1275 | 42.61 | 15.27 | 0.66 |
| 10| 1947 | 52.71 | 21.39 | 0.82 |
| 30| 4978 | 99.21 | 47.66 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.12 | 9.10 | 0.69 |
| 2| 5983 | 36.93 | 12.45 | 0.80 |
| 3| 6150 | 46.58 | 15.79 | 0.91 |
| 4| 6295 | 54.30 | 18.33 | 1.00 |
| 5| 6355 | 60.76 | 20.40 | 1.07 |
| 6| 6519 | 72.43 | 24.40 | 1.20 |
| 7| 6831 | 81.56 | 27.53 | 1.31 |
| 8| 6873 | 90.38 | 30.47 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 567 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 39 | 2219 | 7159 | 99.12 | 37.95 | 1.54 |

