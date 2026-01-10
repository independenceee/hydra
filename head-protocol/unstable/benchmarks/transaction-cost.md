--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-10 04:44:12.34274717 UTC |
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
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.40 | 4.55 | 0.57 |
| 5| 6640 | 18.72 | 5.91 | 0.64 |
| 10| 7647 | 29.18 | 9.20 | 0.79 |
| 43| 14281 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1271 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10078 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 635 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 43.86 | 12.56 | 0.63 |
| 4 | 227 | 858 | 53.42 | 15.24 | 0.73 |
| 5 | 284 | 969 | 64.17 | 18.17 | 0.84 |
| 6 | 337 | 1081 | 75.07 | 21.21 | 0.96 |
| 7 | 393 | 1192 | 78.40 | 22.40 | 1.00 |
| 8 | 451 | 1303 | 89.18 | 25.42 | 1.11 |
| 9 | 507 | 1414 | 88.28 | 25.49 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1820 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.51 | 8.70 | 0.50 |
| 3| 2076 | 27.47 | 9.90 | 0.53 |
| 5| 2405 | 32.15 | 12.56 | 0.61 |
| 10| 3163 | 40.81 | 18.31 | 0.75 |
| 37| 6974 | 89.15 | 49.72 | 1.54 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.54 | 7.31 | 0.41 |
| 2| 766 | 24.32 | 8.46 | 0.44 |
| 3| 894 | 25.16 | 9.35 | 0.46 |
| 5| 1227 | 29.94 | 12.02 | 0.53 |
| 10| 2112 | 42.05 | 18.75 | 0.72 |
| 43| 6650 | 99.27 | 56.62 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.13 | 8.90 | 0.48 |
| 2| 853 | 31.58 | 10.26 | 0.52 |
| 3| 926 | 32.75 | 11.24 | 0.54 |
| 5| 1256 | 37.85 | 14.02 | 0.61 |
| 10| 2020 | 47.66 | 20.11 | 0.77 |
| 37| 6106 | 99.84 | 52.78 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 867 | 36.52 | 11.59 | 0.57 |
| 3| 1006 | 38.51 | 12.80 | 0.60 |
| 5| 1288 | 43.28 | 15.48 | 0.67 |
| 10| 2066 | 53.94 | 21.78 | 0.83 |
| 29| 4920 | 99.05 | 47.01 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.00 | 9.06 | 0.69 |
| 2| 5945 | 35.95 | 12.08 | 0.79 |
| 3| 6160 | 46.02 | 15.52 | 0.90 |
| 4| 6253 | 54.70 | 18.47 | 1.00 |
| 5| 6219 | 57.72 | 19.33 | 1.03 |
| 6| 6331 | 61.25 | 20.44 | 1.07 |
| 7| 6727 | 84.48 | 28.46 | 1.33 |
| 8| 6681 | 83.50 | 27.93 | 1.32 |
| 9| 7036 | 97.22 | 32.71 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.26 | 6.78 | 0.62 |
| 10 | 30 | 1706 | 6852 | 79.97 | 30.44 | 1.32 |
| 10 | 39 | 2221 | 7161 | 98.93 | 37.88 | 1.54 |

