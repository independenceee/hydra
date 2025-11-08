--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-08 04:22:10.871268917 UTC |
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
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14286 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 43.99 | 12.61 | 0.63 |
| 4 | 227 | 858 | 53.74 | 15.32 | 0.73 |
| 5 | 281 | 969 | 60.93 | 17.43 | 0.81 |
| 6 | 339 | 1081 | 66.15 | 19.11 | 0.87 |
| 7 | 395 | 1192 | 81.07 | 23.13 | 1.02 |
| 8 | 451 | 1307 | 87.37 | 24.99 | 1.09 |
| 9 | 506 | 1414 | 93.31 | 26.81 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1922 | 25.47 | 8.70 | 0.50 |
| 3| 2129 | 28.39 | 10.16 | 0.55 |
| 5| 2451 | 32.37 | 12.61 | 0.61 |
| 10| 3141 | 41.76 | 18.58 | 0.76 |
| 38| 7329 | 95.13 | 52.05 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.77 | 7.36 | 0.42 |
| 2| 830 | 25.57 | 8.80 | 0.46 |
| 3| 1002 | 26.95 | 9.86 | 0.48 |
| 5| 1212 | 29.01 | 11.75 | 0.52 |
| 10| 2093 | 41.90 | 18.69 | 0.72 |
| 42| 6580 | 94.66 | 54.72 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.47 | 8.46 | 0.46 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 971 | 33.51 | 11.46 | 0.55 |
| 5| 1216 | 36.91 | 13.75 | 0.60 |
| 10| 1906 | 43.55 | 18.95 | 0.72 |
| 35| 5877 | 96.46 | 50.56 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.83 | 10.16 | 0.53 |
| 2| 890 | 36.56 | 11.60 | 0.57 |
| 3| 895 | 37.20 | 12.40 | 0.58 |
| 5| 1241 | 42.72 | 15.30 | 0.66 |
| 10| 2149 | 55.67 | 22.29 | 0.86 |
| 28| 4760 | 97.39 | 45.91 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.13 | 9.10 | 0.69 |
| 2| 5963 | 35.96 | 12.08 | 0.79 |
| 3| 6171 | 47.25 | 15.94 | 0.92 |
| 4| 6380 | 56.55 | 19.17 | 1.03 |
| 5| 6402 | 65.09 | 21.96 | 1.12 |
| 6| 6625 | 74.49 | 25.13 | 1.22 |
| 7| 6788 | 84.48 | 28.56 | 1.34 |
| 8| 7154 | 95.48 | 32.30 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 20 | 1135 | 6509 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2161 | 7123 | 96.19 | 36.84 | 1.51 |

