--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-21 04:47:53.938294616 UTC |
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
| 1| 5836 | 10.67 | 3.39 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7644 | 29.23 | 9.22 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 747 | 42.55 | 12.28 | 0.62 |
| 4 | 225 | 858 | 51.30 | 14.78 | 0.71 |
| 5 | 281 | 969 | 59.79 | 17.16 | 0.80 |
| 6 | 339 | 1081 | 68.08 | 19.57 | 0.89 |
| 7 | 394 | 1192 | 76.39 | 21.92 | 0.98 |
| 8 | 453 | 1303 | 96.92 | 27.33 | 1.19 |
| 9 | 504 | 1418 | 98.78 | 28.13 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 24.37 | 7.71 | 0.48 |
| 2| 1946 | 25.47 | 8.70 | 0.50 |
| 3| 2058 | 26.86 | 9.75 | 0.53 |
| 5| 2368 | 31.05 | 12.25 | 0.59 |
| 10| 3134 | 40.42 | 18.21 | 0.75 |
| 40| 7734 | 99.41 | 54.60 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 22.77 | 7.36 | 0.42 |
| 2| 699 | 22.62 | 7.96 | 0.42 |
| 3| 943 | 26.10 | 9.60 | 0.47 |
| 5| 1116 | 27.12 | 11.22 | 0.50 |
| 10| 2000 | 40.27 | 18.25 | 0.70 |
| 41| 6417 | 93.21 | 53.65 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 881 | 31.58 | 10.26 | 0.52 |
| 3| 995 | 33.47 | 11.46 | 0.55 |
| 5| 1330 | 38.44 | 14.21 | 0.62 |
| 10| 1946 | 46.83 | 19.87 | 0.76 |
| 35| 5645 | 94.39 | 49.90 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 33.79 | 10.15 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 944 | 37.88 | 12.61 | 0.59 |
| 5| 1370 | 44.02 | 15.70 | 0.68 |
| 10| 1957 | 53.20 | 21.55 | 0.82 |
| 29| 4977 | 99.24 | 47.05 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 26.96 | 9.05 | 0.69 |
| 2| 6013 | 36.89 | 12.44 | 0.80 |
| 3| 6116 | 46.10 | 15.56 | 0.90 |
| 4| 6156 | 54.47 | 18.27 | 0.99 |
| 5| 6336 | 62.19 | 20.98 | 1.08 |
| 6| 6441 | 68.88 | 23.09 | 1.16 |
| 7| 6686 | 79.83 | 26.82 | 1.28 |
| 8| 6753 | 85.92 | 28.89 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.61 | 5.87 | 0.59 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 30 | 1708 | 6855 | 79.15 | 30.16 | 1.31 |
| 10 | 38 | 2165 | 7127 | 96.19 | 36.84 | 1.51 |

