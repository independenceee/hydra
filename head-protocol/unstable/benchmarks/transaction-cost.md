--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-02 04:40:29.48912894 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 19.08 | 6.04 | 0.64 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 40.16 | 11.66 | 0.59 |
| 4 | 226 | 862 | 50.68 | 14.60 | 0.70 |
| 5 | 282 | 969 | 55.95 | 16.26 | 0.76 |
| 6 | 338 | 1081 | 66.51 | 19.20 | 0.87 |
| 7 | 395 | 1196 | 76.59 | 21.97 | 0.98 |
| 8 | 450 | 1303 | 83.45 | 24.10 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.85 | 8.50 | 0.50 |
| 3| 2086 | 27.43 | 9.89 | 0.54 |
| 5| 2276 | 29.18 | 11.72 | 0.57 |
| 10| 3099 | 40.12 | 18.10 | 0.74 |
| 39| 7440 | 96.46 | 53.07 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.84 | 7.39 | 0.42 |
| 2| 758 | 24.01 | 8.38 | 0.44 |
| 3| 929 | 26.67 | 9.80 | 0.48 |
| 5| 1258 | 30.97 | 12.31 | 0.54 |
| 10| 2087 | 41.55 | 18.61 | 0.71 |
| 40| 6670 | 98.48 | 54.43 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 27.54 | 8.47 | 0.46 |
| 2| 811 | 29.15 | 9.59 | 0.49 |
| 3| 902 | 30.15 | 10.52 | 0.51 |
| 5| 1315 | 37.58 | 13.96 | 0.61 |
| 10| 2015 | 45.18 | 19.46 | 0.74 |
| 36| 5991 | 97.74 | 51.58 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.87 | 10.16 | 0.53 |
| 2| 895 | 36.56 | 11.60 | 0.57 |
| 3| 1027 | 38.62 | 12.83 | 0.60 |
| 5| 1272 | 42.60 | 15.27 | 0.66 |
| 10| 2034 | 53.91 | 21.77 | 0.83 |
| 29| 4846 | 97.98 | 46.70 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5797 | 27.09 | 9.08 | 0.69 |
| 2| 5927 | 35.85 | 12.07 | 0.79 |
| 3| 6039 | 43.51 | 14.58 | 0.87 |
| 4| 6249 | 51.29 | 17.28 | 0.96 |
| 5| 6345 | 60.66 | 20.38 | 1.07 |
| 6| 6297 | 64.01 | 21.42 | 1.10 |
| 7| 6740 | 79.53 | 26.74 | 1.28 |
| 8| 6871 | 90.08 | 30.38 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 283 | 6003 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 567 | 6171 | 38.37 | 14.06 | 0.83 |
| 10 | 20 | 1139 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1704 | 6850 | 81.11 | 30.83 | 1.33 |
| 10 | 39 | 2218 | 7157 | 98.49 | 37.73 | 1.53 |

