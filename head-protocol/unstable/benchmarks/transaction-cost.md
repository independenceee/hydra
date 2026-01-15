--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-15 04:52:57.145675193 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7644 | 29.18 | 9.20 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 640 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 42.34 | 12.17 | 0.61 |
| 4 | 226 | 858 | 53.86 | 15.34 | 0.73 |
| 5 | 281 | 969 | 60.45 | 17.31 | 0.81 |
| 6 | 339 | 1081 | 69.80 | 19.91 | 0.91 |
| 7 | 394 | 1192 | 76.93 | 22.14 | 0.98 |
| 8 | 448 | 1303 | 80.44 | 23.28 | 1.03 |
| 9 | 504 | 1414 | 89.23 | 25.89 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1753 | 23.30 | 7.41 | 0.47 |
| 2| 1882 | 24.47 | 8.41 | 0.49 |
| 3| 2180 | 29.42 | 10.45 | 0.56 |
| 5| 2393 | 31.18 | 12.30 | 0.60 |
| 10| 3167 | 40.58 | 18.25 | 0.75 |
| 38| 7346 | 94.21 | 51.81 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 818 | 25.52 | 8.80 | 0.46 |
| 3| 951 | 26.13 | 9.61 | 0.47 |
| 5| 1174 | 29.03 | 11.75 | 0.52 |
| 10| 1891 | 37.61 | 17.49 | 0.66 |
| 43| 6758 | 98.29 | 56.36 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 29.17 | 8.91 | 0.48 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 1068 | 32.36 | 11.19 | 0.54 |
| 5| 1164 | 33.66 | 12.83 | 0.57 |
| 10| 2150 | 46.47 | 19.84 | 0.76 |
| 38| 5934 | 97.42 | 52.68 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 837 | 35.92 | 11.40 | 0.56 |
| 3| 1031 | 38.59 | 12.82 | 0.60 |
| 5| 1255 | 42.53 | 15.25 | 0.66 |
| 10| 2010 | 53.91 | 21.77 | 0.83 |
| 28| 4964 | 98.68 | 46.33 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.13 | 9.10 | 0.69 |
| 2| 5822 | 31.52 | 10.48 | 0.74 |
| 3| 6094 | 45.77 | 15.44 | 0.90 |
| 4| 6376 | 55.80 | 18.86 | 1.02 |
| 5| 6535 | 65.49 | 22.19 | 1.13 |
| 6| 6618 | 73.51 | 24.83 | 1.21 |
| 7| 6628 | 79.61 | 26.73 | 1.28 |
| 8| 6772 | 88.75 | 29.82 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 567 | 6171 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1711 | 6857 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2273 | 7189 | 99.66 | 38.24 | 1.55 |

