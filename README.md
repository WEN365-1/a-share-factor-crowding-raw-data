# Raw data for the A-share factor crowding project

This private repository contains the raw daily market data and exchange margin-financing files used by the companion research repository:

https://github.com/WEN365-1/a-share-factor-crowding-research

## Structure

- `data/raw/daily/3/<code-prefix>/<code>.parquet`: Baostock unadjusted daily bars, one file per stock.
- `data/raw/margin/sse/<YYYYMMDD>.parquet`: Shanghai Stock Exchange margin-financing detail.
- `data/raw/margin/szse/<YYYYMMDD>.parquet`: Shenzhen Stock Exchange margin-financing detail.

## Provenance and use

The files are retained for reproducibility. Redistribution and reuse remain subject to the terms of the upstream data providers. The companion repository contains the cleaned/derived data, code, paper, reports, and evidence manifest.

## Download

Raw data are distributed as a compressed release asset because the uncompressed tree contains more than 10,000 individual files:

https://github.com/WEN365-1/a-share-factor-crowding-raw-data/releases/tag/v1.0-data

Download `raw_data.tar.zst`, then extract from the repository root:

```bash
tar --zstd -xf raw_data.tar.zst
```

This recreates `data/raw/daily/` and `data/raw/margin/`.

## Checksum

```text
f3cff4a27805d82caaccb49e1e451c5244beb9c2cff1ad1fe181cd103d05145f  raw_data.tar.zst
```

Verify with:

```bash
sha256sum -c raw_data.tar.zst.sha256
```
