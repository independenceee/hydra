--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-22 04:52:06.845235697 UTC |
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
| 1| 5836 | 10.85 | 3.45 | 0.52 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 40.16 | 11.69 | 0.59 |
| 4 | 226 | 862 | 53.60 | 15.28 | 0.73 |
| 5 | 283 | 969 | 57.76 | 16.67 | 0.78 |
| 6 | 338 | 1081 | 69.81 | 19.95 | 0.91 |
| 7 | 395 | 1192 | 80.64 | 22.98 | 1.02 |
| 8 | 448 | 1303 | 83.44 | 24.10 | 1.06 |
| 9 | 507 | 1418 | 91.49 | 26.38 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.29 | 7.69 | 0.48 |
| 2| 1984 | 26.96 | 9.09 | 0.52 |
| 3| 2055 | 26.94 | 9.77 | 0.53 |
| 5| 2280 | 28.93 | 11.66 | 0.57 |
| 10| 3119 | 41.02 | 18.36 | 0.75 |
| 43| 7852 | 97.47 | 56.02 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.38 | 0.41 |
| 2| 697 | 22.62 | 7.95 | 0.42 |
| 3| 945 | 26.90 | 9.84 | 0.48 |
| 5| 1313 | 32.56 | 12.74 | 0.56 |
| 10| 2045 | 38.81 | 17.83 | 0.68 |
| 43| 6740 | 97.98 | 56.31 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 27.50 | 8.46 | 0.46 |
| 2| 845 | 29.19 | 9.60 | 0.49 |
| 3| 915 | 32.76 | 11.24 | 0.54 |
| 5| 1282 | 35.01 | 13.24 | 0.58 |
| 10| 1989 | 47.17 | 19.97 | 0.76 |
| 38| 6112 | 98.91 | 53.17 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 969 | 37.80 | 12.59 | 0.59 |
| 5| 1158 | 41.18 | 14.84 | 0.64 |
| 10| 1939 | 52.86 | 21.43 | 0.82 |
| 28| 4925 | 97.95 | 46.09 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.96 | 9.06 | 0.69 |
| 2| 5845 | 31.55 | 10.49 | 0.74 |
| 3| 6073 | 44.91 | 15.11 | 0.89 |
| 4| 6361 | 55.81 | 18.85 | 1.02 |
| 5| 6552 | 66.50 | 22.43 | 1.14 |
| 6| 6411 | 68.94 | 23.07 | 1.16 |
| 7| 6718 | 80.86 | 27.26 | 1.30 |
| 8| 6830 | 90.97 | 30.71 | 1.41 |
| 9| 6891 | 92.19 | 30.94 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.59 | 7.34 | 0.64 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1708 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2162 | 7124 | 95.56 | 36.62 | 1.50 |

