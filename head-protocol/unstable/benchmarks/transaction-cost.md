--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-18 05:06:19.602171086 UTC |
| _Max. memory units_ | 14000000 |
| _Max. CPU units_ | 10000000000 |
| _Max. tx size (kB)_ | 16384 |

## Script summary

| Name   | Hash | Size (Bytes) 
| :----- | :--- | -----------: 
| νHead | fd75e24c9ea915ce8e48d3ff1d0c54ad09cc01191c24416ad7dba4a3 | 11621 | 
| μHead | 83a964e973c065bbe70588f5e089817f92182ae81743e7a54cf3e29e* | 4856 | 
| νDeposit | c78e8c9205721eb3ef4410f3db9c6169fa6db497c24641d29c20529c | 1615 | 
| νCRS | 09db7ee6cf7a4b358dd5c8a2f19d2c048336ffc5a01ef35a47ca7072 | 2736 | 

* The minting policy hash is only usable for comparison. As the script is parameterized, the actual script is unique per head.

## `Init` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5355 | 9.36 | 3.10 | 0.48 |
| 2| 5445 | 9.18 | 3.01 | 0.49 |
| 3| 5544 | 10.19 | 3.35 | 0.50 |
| 5| 5737 | 10.91 | 3.57 | 0.52 |
| 10| 6217 | 13.57 | 4.42 | 0.57 |
| 50| 10063 | 34.77 | 11.05 | 0.95 |
| 100| 14858 | 61.53 | 19.40 | 1.44 |
| 115| 16299 | 70.04 | 22.10 | 1.59 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 2278 | 18.33 | 6.59 | 0.45 |
| 2| 2407 | 19.21 | 7.49 | 0.47 |
| 3| 2540 | 19.77 | 8.27 | 0.48 |
| 5| 2807 | 22.16 | 10.27 | 0.53 |
| 10| 3459 | 26.30 | 14.65 | 0.62 |
| 50| 8697 | 66.22 | 51.73 | 1.44 |
| 75| 11974 | 90.05 | 74.53 | 1.94 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 599 | 16.01 | 5.75 | 0.35 |
| 2| 731 | 16.94 | 6.65 | 0.37 |
| 3| 861 | 17.81 | 7.54 | 0.39 |
| 5| 1123 | 19.60 | 9.34 | 0.43 |
| 10| 1780 | 24.03 | 13.82 | 0.52 |
| 50| 7019 | 62.24 | 50.33 | 1.32 |
| 75| 10299 | 85.44 | 72.95 | 1.82 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 596 | 15.47 | 10.37 | 0.38 |
| 2| 720 | 16.37 | 11.27 | 0.40 |
| 3| 850 | 17.29 | 12.18 | 0.42 |
| 10| 1773 | 23.66 | 18.51 | 0.55 |
| 75| 10284 | 86.42 | 78.17 | 1.86 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 18.78 | 13.47 | 0.43 |
| 2| 750 | 19.87 | 14.44 | 0.45 |
| 3| 877 | 20.97 | 15.40 | 0.47 |
| 5| 1149 | 23.10 | 17.30 | 0.51 |
| 10| 1804 | 28.49 | 22.08 | 0.62 |
| 50| 7048 | 73.58 | 60.72 | 1.49 |
| 73| 10058 | 99.73 | 83.00 | 2.00 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5529 | 22.68 | 41.73 | 0.88 |
| 10 | 1 | 57 | 5563 | 25.03 | 44.25 | 0.92 |
| 10 | 5 | 283 | 5697 | 35.28 | 54.57 | 1.08 |
| 10 | 10 | 571 | 5870 | 49.29 | 67.85 | 1.30 |
| 10 | 20 | 1138 | 6207 | 81.82 | 95.83 | 1.78 |
| 10 | 20 | 1139 | 6208 | 81.82 | 95.83 | 1.78 |


## `PartialFanOut` transaction costs
Largest chunk of ada-only outputs that can be distributed in one partial fanout step, computed dynamically. The last row is the maximum total UTxO count where at least one output can still be distributed.

| Distributed | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| ----------: | -----------: | ------: | --------: | --------: | --------: |
| 11 | 570 | 987 | 34.31 | 65.19 | 0.94 |
| 25 | 1310 | 1429 | 67.64 | 98.26 | 1.47 |
| 30 | 1307 | 1426 | 67.64 | 98.26 | 1.47 |
| 40 | 1308 | 1423 | 67.64 | 98.26 | 1.47 |
| 50 | 1310 | 1429 | 67.64 | 98.26 | 1.47 |
| 100 | 1311 | 1430 | 67.64 | 98.26 | 1.47 |
| 150 | 1311 | 1426 | 67.64 | 98.26 | 1.47 |
| 200 | 1309 | 1428 | 67.64 | 98.26 | 1.47 |
| 200 | 1308 | 1427 | 67.64 | 98.26 | 1.47 |


## `PartialFanOut` transaction costs (with native tokens)
Largest chunk of native-token outputs that can be distributed in one partial fanout step, computed dynamically. The last row is the maximum total UTxO count where at least one output can still be distributed.

| Distributed | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| ----------: | -----------: | ------: | --------: | --------: | --------: |
| 11 | 970 | 1444 | 41.38 | 67.69 | 1.04 |
| 25 | 2583 | 2852 | 75.99 | 98.13 | 1.60 |
| 30 | 2184 | 2434 | 75.97 | 98.02 | 1.58 |
| 40 | 2583 | 2848 | 75.97 | 98.13 | 1.60 |
| 50 | 2184 | 2435 | 75.99 | 98.03 | 1.58 |
| 100 | 2016 | 2259 | 75.99 | 97.98 | 1.57 |
| 150 | 2352 | 2607 | 75.99 | 98.08 | 1.59 |
| 200 | 2541 | 2809 | 75.97 | 98.13 | 1.60 |
| 200 | 2499 | 2765 | 75.97 | 98.12 | 1.59 |


## `FinalPartialFanOut` transaction costs (with native tokens)
Terminal partial fanout step (FanoutProgress → Final) with outputs carrying a native token. Burns all head tokens and proves accumulator exhaustion via BLS proof.

| Distributed | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| ----------: | -----------: | ------: | --------: | --------: | --------: |
| 1 | 97 | 5401 | 21.42 | 43.15 | 0.87 |
| 5 | 615 | 5835 | 35.15 | 54.73 | 1.09 |
| 10 | 1040 | 6156 | 53.23 | 69.47 | 1.35 |
| 10 | 1010 | 6126 | 53.35 | 69.48 | 1.35 |

