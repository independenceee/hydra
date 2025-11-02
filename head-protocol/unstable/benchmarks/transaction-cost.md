--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-02 11:16:20.715739077 UTC |
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
| 1| 5838 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6240 | 15.07 | 4.78 | 0.58 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7650 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 915 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2160 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 43.99 | 12.61 | 0.63 |
| 4 | 228 | 858 | 53.93 | 15.36 | 0.73 |
| 5 | 283 | 969 | 58.14 | 16.77 | 0.78 |
| 6 | 338 | 1085 | 69.83 | 19.92 | 0.91 |
| 7 | 394 | 1192 | 87.16 | 24.59 | 1.08 |
| 8 | 449 | 1303 | 87.97 | 25.24 | 1.10 |
| 9 | 505 | 1414 | 95.05 | 27.22 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.37 | 7.71 | 0.48 |
| 2| 1942 | 25.47 | 8.70 | 0.50 |
| 3| 2192 | 29.47 | 10.46 | 0.56 |
| 5| 2424 | 31.99 | 12.52 | 0.61 |
| 10| 3178 | 41.96 | 18.62 | 0.76 |
| 41| 7745 | 99.58 | 55.29 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.81 | 7.37 | 0.42 |
| 2| 696 | 22.62 | 7.97 | 0.42 |
| 3| 901 | 25.52 | 9.47 | 0.46 |
| 5| 1183 | 29.22 | 11.81 | 0.52 |
| 10| 1962 | 39.15 | 17.96 | 0.68 |
| 42| 6846 | 99.90 | 56.17 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 825 | 29.15 | 9.59 | 0.49 |
| 3| 948 | 30.87 | 10.74 | 0.52 |
| 5| 1172 | 36.27 | 13.55 | 0.59 |
| 10| 2057 | 45.65 | 19.59 | 0.75 |
| 36| 5786 | 96.08 | 51.01 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.83 | 10.15 | 0.53 |
| 2| 815 | 35.85 | 11.38 | 0.56 |
| 3| 1019 | 38.55 | 12.81 | 0.60 |
| 5| 1326 | 43.20 | 15.45 | 0.67 |
| 10| 2119 | 55.17 | 22.16 | 0.85 |
| 29| 4852 | 97.84 | 46.63 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 27.05 | 9.07 | 0.69 |
| 2| 5984 | 36.84 | 12.42 | 0.80 |
| 3| 6136 | 46.15 | 15.54 | 0.91 |
| 4| 6142 | 49.00 | 16.40 | 0.93 |
| 5| 6424 | 62.64 | 21.13 | 1.09 |
| 6| 6579 | 71.47 | 24.08 | 1.19 |
| 7| 6606 | 81.92 | 27.52 | 1.30 |
| 8| 6718 | 85.25 | 28.60 | 1.34 |
| 10| 6805 | 96.15 | 32.26 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.23 | 6.09 | 0.60 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1710 | 6856 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2221 | 7160 | 99.82 | 38.19 | 1.55 |

