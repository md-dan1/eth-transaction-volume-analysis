This folder contains the 2025 Ethereum transaction volume for the tracked coins
listed in `top_coins_by_tx_count.txt`. All values are in USD.

- `data_2025.csv`: Semicolon-delimited, one row per block (`block_number;timestamp;<coins…>`). The coin columns correspond to the top 20 coins listed in `top_coins_by_tx_count.txt`. The first 64 blocks serve as a warm-up phase, during which the delta window is being filled.