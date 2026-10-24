# Raw-data documentation for the A-share factor crowding project

This repository now provides documentation only. It does not distribute raw provider data or stand-alone provider-derived datasets.

The companion research repository is:

https://github.com/WEN365-1/a-share-factor-crowding-research

## Original input structure

The research code documents the following local input structure for researchers who independently obtain the data under the upstream providers' terms:

- `data/raw/daily/3/<code-prefix>/<code>.parquet`: Baostock unadjusted daily bars, one file per stock.
- `data/raw/margin/sse/<YYYYMMDD>.parquet`: Shanghai Stock Exchange margin-financing detail.
- `data/raw/margin/szse/<YYYYMMDD>.parquet`: Shenzhen Stock Exchange margin-financing detail.

## Public-release status

The former `v1.0-data` public release and its compressed raw-data asset were removed on 2026-10-25 after the author authorized suspension while asset-specific redistribution permission remains unresolved. A private archival copy was retained and verified before removal. The historical release must not be interpreted as evidence of continuing redistribution permission.

No replacement public download is provided. Do not use historical download links or checksum files as current acquisition instructions.

## Lawful reconstruction

Researchers must obtain the required inputs directly from Baostock, the Shanghai Stock Exchange, and the Shenzhen Stock Exchange under their applicable terms, then construct the analysis inputs using the companion repository's code and documentation. The public package alone does not reproduce the empirical results.

If written permission later covers specific assets, only the covered assets and matching acquisition or redistribution instructions may be restored. Non-commercial research use, API accessibility, transformation, or aggregation alone is not treated as proof of redistribution permission.
