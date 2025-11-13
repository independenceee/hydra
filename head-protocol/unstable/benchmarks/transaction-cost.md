--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-13 04:35:38.321522591 UTC |
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
| 1| 5837 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6242 | 14.78 | 4.68 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 924 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 169 | 751 | 43.80 | 12.53 | 0.63 |
| 4 | 226 | 858 | 48.50 | 14.11 | 0.68 |
| 5 | 284 | 969 | 60.86 | 17.41 | 0.81 |
| 6 | 339 | 1081 | 66.48 | 19.23 | 0.87 |
| 7 | 394 | 1192 | 74.79 | 21.62 | 0.96 |
| 8 | 450 | 1303 | 87.45 | 25.06 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1788 | 23.92 | 7.60 | 0.48 |
| 2| 1880 | 24.85 | 8.50 | 0.50 |
| 3| 2098 | 28.47 | 10.18 | 0.55 |
| 5| 2546 | 34.10 | 13.11 | 0.63 |
| 10| 3097 | 39.99 | 18.07 | 0.74 |
| 41| 7558 | 96.26 | 54.38 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.57 | 7.33 | 0.41 |
| 2| 797 | 24.05 | 8.40 | 0.44 |
| 3| 1066 | 27.65 | 10.07 | 0.49 |
| 5| 1168 | 28.49 | 11.65 | 0.52 |
| 10| 2004 | 38.50 | 17.74 | 0.68 |
| 40| 6572 | 99.84 | 54.75 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 1061 | 32.21 | 11.15 | 0.54 |
| 5| 1314 | 35.72 | 13.46 | 0.59 |
| 10| 2026 | 45.04 | 19.42 | 0.74 |
| 36| 5781 | 94.90 | 50.68 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 33.83 | 10.15 | 0.53 |
| 2| 852 | 36.64 | 11.62 | 0.57 |
| 3| 969 | 37.84 | 12.60 | 0.59 |
| 5| 1264 | 42.56 | 15.26 | 0.66 |
| 10| 2015 | 54.65 | 21.99 | 0.84 |
| 28| 4697 | 94.39 | 45.01 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5841 | 26.96 | 9.06 | 0.69 |
| 2| 5942 | 36.04 | 12.09 | 0.79 |
| 3| 6109 | 42.36 | 14.22 | 0.86 |
| 4| 6195 | 50.71 | 17.00 | 0.96 |
| 5| 6454 | 60.90 | 20.56 | 1.07 |
| 6| 6475 | 71.15 | 23.94 | 1.18 |
| 7| 6595 | 76.35 | 25.70 | 1.24 |
| 8| 6942 | 93.67 | 31.65 | 1.44 |
| 9| 7021 | 99.82 | 33.56 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 568 | 6172 | 40.76 | 14.88 | 0.86 |
| 10 | 20 | 1137 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1710 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2219 | 7158 | 99.38 | 38.04 | 1.54 |

