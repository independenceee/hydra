--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-14 04:59:34.748631485 UTC |
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
| 1| 5837 | 10.66 | 3.39 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7650 | 29.02 | 9.14 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 171 | 747 | 39.97 | 11.62 | 0.59 |
| 4 | 225 | 858 | 53.92 | 15.36 | 0.73 |
| 5 | 282 | 969 | 55.91 | 16.22 | 0.76 |
| 6 | 337 | 1081 | 67.94 | 19.57 | 0.89 |
| 7 | 395 | 1192 | 72.55 | 21.08 | 0.94 |
| 8 | 448 | 1303 | 94.32 | 26.70 | 1.16 |
| 10 | 561 | 1525 | 97.10 | 28.06 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1988 | 26.96 | 9.09 | 0.52 |
| 3| 2017 | 25.87 | 9.47 | 0.52 |
| 5| 2417 | 32.00 | 12.52 | 0.61 |
| 10| 3396 | 44.53 | 19.34 | 0.80 |
| 41| 7669 | 97.28 | 54.69 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.53 | 7.32 | 0.41 |
| 2| 752 | 23.62 | 8.23 | 0.43 |
| 3| 938 | 26.06 | 9.59 | 0.47 |
| 5| 1274 | 32.37 | 12.69 | 0.56 |
| 10| 2103 | 42.28 | 18.80 | 0.72 |
| 39| 6529 | 97.63 | 53.51 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 27.51 | 8.47 | 0.46 |
| 2| 779 | 30.94 | 10.07 | 0.51 |
| 3| 1011 | 34.18 | 11.67 | 0.56 |
| 5| 1264 | 35.01 | 13.24 | 0.58 |
| 10| 1998 | 47.43 | 20.04 | 0.77 |
| 35| 5720 | 94.62 | 49.97 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.79 | 10.15 | 0.53 |
| 2| 863 | 36.56 | 11.60 | 0.57 |
| 3| 1006 | 38.66 | 12.84 | 0.60 |
| 5| 1209 | 41.97 | 15.07 | 0.65 |
| 10| 1981 | 53.16 | 21.54 | 0.82 |
| 28| 4993 | 99.17 | 46.45 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 26.97 | 9.05 | 0.69 |
| 2| 6021 | 37.00 | 12.47 | 0.80 |
| 3| 6102 | 44.92 | 15.11 | 0.89 |
| 4| 6241 | 53.86 | 18.12 | 0.99 |
| 5| 6409 | 60.27 | 20.26 | 1.07 |
| 6| 6669 | 73.90 | 25.02 | 1.22 |
| 7| 6641 | 79.32 | 26.65 | 1.28 |
| 8| 6934 | 91.79 | 30.99 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7160 | 98.93 | 37.88 | 1.54 |

