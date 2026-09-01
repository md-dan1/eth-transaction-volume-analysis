# 1,000 blocks after Fusaka block 23935694
all instances start with a window fill-up phase

## delta 32
Samples (n):  1001
Blocks:       23936694 - 23944894
Delta-Blocks: 32

Min:          0.286 ms
Median (p50): 3.407 ms
Mean:         4.879 ms
p90:          10.507 ms
p95:          12.141 ms
p99:          18.002 ms
Max:          19.244 ms
IQR:          2.494 ms
Stdev:        3.725 ms
Per TX Mean:  0.017 ms
Mean TX per block: 337.815 tx/block

Memory (final state)

Active vertices:     8,668
Blocks in window:    33
TXs in window:       10,555

Total instance:      7.4 MiB  (7,769,676 B)
  vertex_map:        1.3 MiB  (18.2 %)
  previous_tx:       6.5 MiB  (87.2 %)
  shared/overlap:    410.5 KiB  (5.4 %)

Per vertex:          162.9 B
Per TX in window:    642.2 B
Model:               M ~ 162.9 * n_vertices + 642.2 * n_txs + const

Current allocated:   37.7 MiB
Peak allocated:      58.6 MiB
Peak / total:        7.91x

## delta 64
Samples (n):  1001
Blocks:       23936694 - 23944894
Delta-Blocks: 64

Min:          0.216 ms
Median (p50): 3.656 ms
Mean:         5.152 ms
p90:          11.061 ms
p95:          12.431 ms
p99:          18.430 ms
Max:          24.782 ms
IQR:          2.829 ms
Stdev:        3.786 ms
Per TX Mean:  0.018 ms
Mean TX per block: 337.815 tx/block

Memory (final state)

Active vertices:     13,880
Blocks in window:    65
TXs in window:       20,979

Total instance:      15.4 MiB  (16,166,765 B)
  vertex_map:        3.4 MiB  (21.8 %)
  previous_tx:       12.9 MiB  (83.3 %)
  shared/overlap:    807.4 KiB  (5.1 %)

Per vertex:          253.5 B
Per TX in window:    642.3 B

Current allocated:   52.1 MiB
Peak allocated:      65.3 MiB
Peak / total:        4.24x

## delta 300
Samples (n):  1001
Blocks:       23936694 - 23944894
Delta-Blocks: 300

Min:          0.250 ms
Median (p50): 3.745 ms
Mean:         4.842 ms
p90:          10.104 ms
p95:          11.717 ms
p99:          16.712 ms
Max:          23.212 ms
IQR:          2.279 ms
Stdev:        3.196 ms
Per TX Mean:  0.018 ms
Mean TX per block: 337.815 tx/block

Memory (final state)

Active vertices:     120,426
Blocks in window:    296
TXs in window:       162,869

Total instance:      112.0 MiB  (117,434,589 B)
  vertex_map:        20.5 MiB  (18.3 %)
  previous_tx:       100.4 MiB  (89.7 %)
  shared/overlap:    9.0 MiB  (8.0 %)

Per vertex:          178.9 B
Per TX in window:    646.6 B + 646.6 * n_txs + const

Current allocated:   238.6 MiB
Peak allocated:      305.8 MiB
Peak / total:        2.73x

## delta 7200
Samples (n):  1001
Blocks:       23936694 - 23944894
Delta-Blocks: 7200

Min:          0.300 ms
Median (p50): 3.491 ms
Mean:         4.255 ms
p90:          8.772 ms
p95:          10.288 ms
p99:          12.145 ms
Max:          15.623 ms
IQR:          3.163 ms
Stdev:        2.802 ms
Per TX Mean:  0.014 ms
Mean TX per block: 337.815 tx/block
23944893 block [03:50, 40.30 block/s]
Memory (final state)

Active vertices:     689,217
Blocks in window:    6,985
TXs in window:       2,406,138

Total instance:      1.5 GiB  (1,603,884,859 B)
  vertex_map:        104.9 MiB  (6.9 %)
  previous_tx:       1.4 GiB  (96.5 %)
  shared/overlap:    51.0 MiB  (3.3 %)

Per vertex:          159.6 B
Per TX in window:    643.1 B + 643.1 * n_txs + const

Current allocated:   2.5 GiB
Peak allocated:      3.6 GiB
Peak / total:        2.40x