| Method         |   N=2 (ms) |   N=4 (ms) |   N=8 (ms) |   N=16 (ms) |
|:---------------|-----------:|-----------:|-----------:|------------:|
| base           |      0.000 |      0.000 |      0.000 |       0.000 |
| shrunk         |      0.000 |      0.000 |      0.000 |       0.000 |
| shrunk + cuda  |      0.013 |      0.024 |      0.038 |       0.066 |
| base + cuda    |      1.888 |      3.770 |      7.530 |      15.048 |
| half + cuda    |      0.957 |      1.899 |      3.780 |       7.540 |
| bounded + cuda |      0.510 |      0.995 |      1.964 |       3.898 |
| tiled + cuda   |      0.370 |      0.700 |      1.353 |       2.663 |