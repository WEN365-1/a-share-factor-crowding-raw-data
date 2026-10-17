# Raw data for the A-share factor crowding project

This private repository contains the raw daily market data and exchange margin-financing files used by the companion research repository:

https://github.com/WEN365-1/a-share-factor-crowding-research

## Structure

- `data/raw/daily/3/<code-prefix>/<code>.parquet`: Baostock unadjusted daily bars, one file per stock.
- `data/raw/margin/sse/<YYYYMMDD>.parquet`: Shanghai Stock Exchange margin-financing detail.
- `data/raw/margin/szse/<YYYYMMDD>.parquet`: Shenzhen Stock Exchange margin-financing detail.

## Provenance and use

The files are retained for reproducibility. Redistribution and reuse remain subject to the terms of the upstream data providers. The companion repository contains the cleaned/derived data, code, paper, reports, and evidence manifest.
