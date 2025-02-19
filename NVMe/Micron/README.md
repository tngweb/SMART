Micron NVMe Drives
==================

This is a list of all tested Micron NVMe drive models and their MTBFs. See more
info on reliability test in the [README](https://github.com/linuxhw/SMART).

NVME by Model
------------

Please take all columns into account when reading the table. Pay attention on the
number of tested samples and power-on days. Simultaneous high values of both MTBF
and errors are possible if only rare drives in the subset encounter errors.

Days - avg. days per sample,
Err  - avg. errors per sample,
MTBF - avg. MTBF in years per sample.

| MFG       | Model              | Size   | Samples | Days  | Err   | MTBF |
|-----------|--------------------|--------|---------|-------|-------|------|
| Micron    | MTFDHAL3T2MCE-1... | 3.2 TB | 1       | 424   | 0     | 1.16   |
| Micron    | 9300_MTFDHAL15T... | 15.... | 3       | 333   | 0     | 0.91   |
| Micron    | 7300_MTFDHBE6T4TDG | 6.4 TB | 2       | 293   | 0     | 0.80   |
| Micron    | 9200_MTFDHAL1T6TCU | 1.6 TB | 1       | 200   | 0     | 0.55   |
| Micron    | 2200V_MTFDHBA25... | 256 GB | 2       | 133   | 0     | 0.37   |
| Micron    | 7400_MTFDKBG3T8TDZ | 3.8 TB | 4       | 106   | 0     | 0.29   |
| Micron    | 2200S NVMe         | 512 GB | 48      | 103   | 0     | 0.28   |
| Micron    | 2200 NVMe          | 512 GB | 2       | 91    | 0     | 0.25   |
| Micron    | 7300_MTFDHBG3T8TDF | 3.8 TB | 1       | 89    | 0     | 0.25   |
| Micron    | 7300_MTFDHBE7T6TDF | 7.6 TB | 5       | 86    | 0     | 0.24   |
| Micron    | 9300_MTFDHAL6T4TDR | 6.4 TB | 2       | 76    | 0     | 0.21   |
| Micron    | 2210 NVMe          | 512 GB | 1       | 75    | 0     | 0.21   |
| Micron    | 2200S NVMe         | 1 TB   | 15      | 72    | 1     | 0.20   |
| Micron    | MTFDHBA512TCK      | 512 GB | 10      | 66    | 0     | 0.18   |
| Micron    | 2200V_MTFDHBA51... | 512 GB | 37      | 63    | 0     | 0.17   |
| Micron    | 2200S NVMe         | 256 GB | 12      | 63    | 0     | 0.17   |
| Micron    | 2450 NVMe          | 1 TB   | 2       | 60    | 0     | 0.17   |
| Micron    | 2450 NVMe          | 512 GB | 1       | 59    | 0     | 0.16   |
| Micron    | 2210_MTFDHBA512QFD | 512 GB | 75      | 54    | 0     | 0.15   |
| Micron    | 7300_MTFDHBE3T8TDF | 3.8 TB | 4       | 33    | 0     | 0.09   |
| Micron    | 2210_MTFDHBA1T0QFD | 1 TB   | 46      | 33    | 0     | 0.09   |
| Micron    | MTFDHBA256TCK-1... | 256 GB | 36      | 31    | 1     | 0.08   |
| Micron    | 2200_MTFDHBA512TCK | 512 GB | 11      | 22    | 0     | 0.06   |
| Micron    | MTFDHBA512QFD      | 512 GB | 63      | 21    | 0     | 0.06   |
| Micron    | 3400 NVMe          | 1 TB   | 7       | 19    | 0     | 0.05   |
| Micron    | 2450_MTFDKBA1T0TFK | 1 TB   | 28      | 17    | 0     | 0.05   |
| Micron    | MTFDKBA256TFK      | 256 GB | 2       | 16    | 0     | 0.05   |
| Micron    | 7300_MTFDHBA480TDF | 480 GB | 1       | 16    | 0     | 0.04   |
| Micron    | 2300 NVMe          | 1 TB   | 56      | 15    | 0     | 0.04   |
| Micron    | MTFDKBA512TFK-1... | 512 GB | 2       | 14    | 0     | 0.04   |
| Micron    | MTFDHBA512QFD-1... | 512 GB | 27      | 14    | 0     | 0.04   |
| Micron    | 2200_MTFDHBA1T0TCK | 1 TB   | 7       | 14    | 0     | 0.04   |
| Micron    | 2200_MTFDHBA256TCK | 256 GB | 10      | 13    | 0     | 0.04   |
| Micron    | 2450_MTFDKBK512TFK | 512 GB | 1       | 13    | 0     | 0.04   |
| Micron    | MTFDHBA1T0TCK      | 1 TB   | 8       | 12    | 0     | 0.03   |
| Micron    | MTFDHBA256TDV      | 256 GB | 8       | 12    | 0     | 0.03   |
| Micron    | 2450_MTFDKBA512TFK | 512 GB | 32      | 10    | 0     | 0.03   |
| Micron    | 2450_MTFDKBK1T0TFK | 1 TB   | 3       | 10    | 0     | 0.03   |
| Micron    | 2300_MTFDHBA256TDV | 256 GB | 2       | 9     | 0     | 0.03   |
| Micron    | 9200_MTFDHAL1T9TCT | 1.9 TB | 1       | 243   | 24    | 0.03   |
| Micron    | MTFDHBA512TDV      | 512 GB | 31      | 8     | 0     | 0.02   |
| Micron    | MTFDKBA1T0TFK      | 1 TB   | 1       | 8     | 0     | 0.02   |
| Micron    | MTFDHBA256TCK      | 256 GB | 7       | 11    | 32    | 0.02   |
| Micron    | MTFDKCD1T0TFK      | 1 TB   | 1       | 8     | 0     | 0.02   |
| Micron    | 2300 NVMe          | 512 GB | 43      | 7     | 1     | 0.02   |
| Micron    | MTFDHBA1T0TDV-1... | 1 TB   | 9       | 6     | 0     | 0.02   |
| Micron    | 3400_MTFDKBA512TFH | 512 GB | 18      | 6     | 0     | 0.02   |
| Micron    | MTFDHBA1T0QFD-1... | 1 TB   | 3       | 5     | 0     | 0.02   |
| Micron    | MTFDKCD256TFK      | 256 GB | 4       | 4     | 0     | 0.01   |
| Micron    | MTFDKCD512TFK      | 512 GB | 15      | 4     | 0     | 0.01   |
| Micron    | MTFDKBA512TFH      | 512 GB | 14      | 4     | 0     | 0.01   |
| Micron    | MTFDHBA256TDV-1... | 256 GB | 3       | 4     | 0     | 0.01   |
| Micron    | 3400_MTFDKBA1T0TFH | 1 TB   | 45      | 3     | 0     | 0.01   |
| Micron    | 2210S NVMe         | 512 GB | 4       | 3     | 0     | 0.01   |
| Micron    | MTFDHBA512TDV-1... | 512 GB | 11      | 3     | 0     | 0.01   |
| Micron    | 3400 NVMe          | 512 GB | 6       | 2     | 0     | 0.01   |
| Micron    | 2300 NVMe          | 256 GB | 1       | 2     | 0     | 0.01   |
| Micron    | MTFDKBA512TFK      | 512 GB | 3       | 2     | 0     | 0.01   |
| Micron    | MTFDKBA1T0TFH-1... | 1 TB   | 8       | 2     | 0     | 0.01   |
| Micron    | MTFDKBA1T0TFH      | 1 TB   | 15      | 2     | 0     | 0.01   |
| Micron    | MTFDHBA1T0QFD      | 1 TB   | 1       | 1     | 0     | 0.00   |
| Micron    | MTFDKBA512TFH-1... | 512 GB | 8       | 1     | 0     | 0.00   |
| Micron    | 7300_MTFDHBE960TDF | 960 GB | 2       | 0     | 0     | 0.00   |
| Micron    | MTFDHBA256TDV-1... | 256 GB | 1       | 0     | 0     | 0.00   |
| Micron    | 2400_MTFDKBA512QFM | 512 GB | 1       | 0     | 0     | 0.00   |
| Micron    | MTFDHBA1T0TDV-1... | 1 TB   | 1       | 33    | 169   | 0.00   |
| Micron    | MTFDHBA512TDV-1... | 512 GB | 1       | 0     | 0     | 0.00   |
