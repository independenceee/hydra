--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-07 04:44:36.751028476 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 12.84 | 4.08 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14279 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 40.12 | 11.65 | 0.59 |
| 4 | 227 | 858 | 51.05 | 14.67 | 0.71 |
| 5 | 282 | 969 | 61.06 | 17.46 | 0.81 |
| 6 | 340 | 1081 | 67.92 | 19.57 | 0.89 |
| 7 | 393 | 1192 | 75.91 | 21.88 | 0.97 |
| 8 | 451 | 1303 | 97.29 | 27.47 | 1.19 |
| 9 | 504 | 1414 | 92.01 | 26.56 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.00 | 7.62 | 0.48 |
| 2| 1931 | 25.47 | 8.70 | 0.50 |
| 3| 2013 | 25.87 | 9.47 | 0.52 |
| 5| 2349 | 30.49 | 12.08 | 0.59 |
| 10| 3047 | 38.85 | 17.75 | 0.73 |
| 39| 7541 | 95.73 | 52.93 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.84 | 7.38 | 0.42 |
| 2| 767 | 24.25 | 8.44 | 0.44 |
| 3| 917 | 27.07 | 9.89 | 0.48 |
| 5| 1187 | 29.92 | 12.01 | 0.53 |
| 10| 1963 | 39.34 | 17.99 | 0.68 |
| 41| 6624 | 98.64 | 55.12 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.13 | 8.90 | 0.48 |
| 2| 737 | 30.19 | 9.84 | 0.50 |
| 3| 983 | 33.32 | 11.42 | 0.55 |
| 5| 1325 | 38.49 | 14.22 | 0.62 |
| 10| 2044 | 45.01 | 19.40 | 0.74 |
| 36| 5846 | 95.13 | 50.78 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.87 | 10.16 | 0.53 |
| 2| 828 | 35.92 | 11.40 | 0.56 |
| 3| 1024 | 39.22 | 13.02 | 0.61 |
| 5| 1294 | 43.36 | 15.49 | 0.67 |
| 10| 2150 | 55.67 | 22.30 | 0.86 |
| 28| 4799 | 97.01 | 45.76 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5788 | 27.16 | 9.10 | 0.69 |
| 2| 5927 | 35.84 | 12.04 | 0.79 |
| 3| 6168 | 46.69 | 15.81 | 0.91 |
| 4| 6192 | 50.37 | 16.87 | 0.95 |
| 5| 6564 | 67.17 | 22.71 | 1.15 |
| 6| 6557 | 73.44 | 24.74 | 1.21 |
| 7| 6662 | 77.56 | 26.12 | 1.26 |
| 8| 6706 | 81.52 | 27.32 | 1.30 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2216 | 7155 | 98.42 | 37.71 | 1.53 |

