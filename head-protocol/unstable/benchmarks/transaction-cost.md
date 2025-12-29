--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-29 05:00:31.75813204 UTC |
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
| 1| 5834 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.69 | 4.65 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 170 | 747 | 40.24 | 11.71 | 0.59 |
| 4 | 227 | 858 | 52.42 | 15.00 | 0.72 |
| 5 | 283 | 969 | 61.23 | 17.56 | 0.81 |
| 6 | 340 | 1081 | 66.23 | 19.09 | 0.87 |
| 7 | 395 | 1192 | 75.09 | 21.74 | 0.97 |
| 8 | 450 | 1307 | 80.31 | 23.24 | 1.02 |
| 9 | 505 | 1418 | 94.66 | 27.36 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.00 | 7.62 | 0.48 |
| 2| 1927 | 25.55 | 8.71 | 0.50 |
| 3| 2139 | 28.38 | 10.16 | 0.55 |
| 5| 2359 | 30.96 | 12.23 | 0.59 |
| 10| 3272 | 42.71 | 18.86 | 0.78 |
| 41| 7714 | 99.31 | 55.21 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.50 | 7.30 | 0.41 |
| 2| 830 | 25.14 | 8.69 | 0.45 |
| 3| 853 | 24.11 | 9.04 | 0.45 |
| 5| 1188 | 28.16 | 11.51 | 0.51 |
| 10| 2022 | 40.37 | 18.27 | 0.70 |
| 42| 6674 | 96.78 | 55.27 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 27.51 | 8.47 | 0.46 |
| 2| 732 | 30.19 | 9.84 | 0.50 |
| 3| 923 | 32.76 | 11.24 | 0.54 |
| 5| 1189 | 36.42 | 13.59 | 0.59 |
| 10| 2060 | 48.23 | 20.28 | 0.78 |
| 35| 5606 | 92.66 | 49.38 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.12 | 9.94 | 0.52 |
| 2| 765 | 35.14 | 11.16 | 0.55 |
| 3| 1002 | 38.63 | 12.83 | 0.60 |
| 5| 1301 | 42.86 | 15.35 | 0.66 |
| 10| 1897 | 52.74 | 21.40 | 0.81 |
| 30| 4982 | 98.57 | 47.49 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 26.97 | 9.07 | 0.69 |
| 2| 5969 | 35.91 | 12.07 | 0.79 |
| 3| 6187 | 46.16 | 15.56 | 0.91 |
| 4| 6305 | 56.15 | 18.95 | 1.02 |
| 5| 6562 | 67.38 | 22.88 | 1.15 |
| 6| 6568 | 70.22 | 23.66 | 1.18 |
| 7| 6890 | 86.08 | 29.14 | 1.36 |
| 8| 6894 | 92.66 | 31.17 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2277 | 7193 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2218 | 7158 | 98.49 | 37.73 | 1.53 |

