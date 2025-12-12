--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-12 04:44:34.918270371 UTC |
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
| 1| 5834 | 10.35 | 3.28 | 0.51 |
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6242 | 15.22 | 4.84 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 99.42 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10044 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 751 | 40.24 | 11.69 | 0.59 |
| 4 | 226 | 858 | 47.89 | 13.88 | 0.68 |
| 5 | 281 | 974 | 56.12 | 16.25 | 0.76 |
| 6 | 338 | 1085 | 73.98 | 21.03 | 0.95 |
| 7 | 393 | 1196 | 87.15 | 24.58 | 1.08 |
| 8 | 451 | 1307 | 83.21 | 23.99 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 24.29 | 7.69 | 0.48 |
| 2| 1955 | 25.80 | 8.77 | 0.51 |
| 3| 2102 | 28.39 | 10.16 | 0.55 |
| 5| 2388 | 31.57 | 12.38 | 0.60 |
| 10| 3258 | 43.52 | 19.06 | 0.78 |
| 37| 7324 | 95.02 | 51.35 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 615 | 22.57 | 7.31 | 0.41 |
| 2| 780 | 23.59 | 8.23 | 0.43 |
| 3| 901 | 25.49 | 9.46 | 0.46 |
| 5| 1220 | 29.18 | 11.80 | 0.52 |
| 10| 2143 | 43.54 | 19.13 | 0.73 |
| 39| 6267 | 92.60 | 52.13 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 29.13 | 8.90 | 0.48 |
| 2| 808 | 29.26 | 9.62 | 0.49 |
| 3| 948 | 30.94 | 10.75 | 0.52 |
| 5| 1275 | 37.73 | 13.99 | 0.61 |
| 10| 2234 | 46.96 | 20.00 | 0.77 |
| 36| 6097 | 99.52 | 52.06 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.87 | 10.16 | 0.53 |
| 2| 889 | 36.56 | 11.60 | 0.57 |
| 3| 899 | 37.24 | 12.41 | 0.58 |
| 5| 1239 | 42.65 | 15.28 | 0.66 |
| 10| 2123 | 54.95 | 22.09 | 0.85 |
| 29| 5031 | 99.66 | 47.22 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.00 | 9.07 | 0.69 |
| 2| 5917 | 34.91 | 11.68 | 0.78 |
| 3| 6132 | 45.72 | 15.43 | 0.90 |
| 4| 6232 | 54.36 | 18.35 | 1.00 |
| 5| 6312 | 58.84 | 19.75 | 1.05 |
| 6| 6592 | 72.17 | 24.35 | 1.20 |
| 7| 6586 | 80.19 | 26.95 | 1.28 |
| 8| 6902 | 94.72 | 32.00 | 1.45 |
| 9| 7045 | 99.89 | 33.71 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1134 | 6508 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

