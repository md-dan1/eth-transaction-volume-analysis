This folder contains the 2025 Ethereum transaction volume per block for each delta and algorithm. All values are in USD.

- `data_2025.csv`: Semicolon-separated, with one row per block
  (`block_number;timestamp;<algo>_<delta>...`). A column `<algo>_<N>` shows how much volume this block contributes to a window of `N + 1` blocks. The first 64 blocks are used as a warm-up while the delta window is being filled.

- `block_contribution_per_delta_and_algo.png`: Shows the average contribution per block over the whole year, with one bar for each algorithm and delta. The matching `.csv` contains the values used for the chart (`algorithm;delta;avg_per_block_M`, where `M` means millions of USD).

- `daily_volume_per_delta.png`: Shows the daily average and maximum volume per block for selected deltas, with one line per algorithm. The matching `.csv` contains the values used for the chart (`day;delta;algorithm;avg_per_block_M;max_per_block_M`).
