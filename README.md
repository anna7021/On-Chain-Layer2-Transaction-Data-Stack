# On-Chain-Layer2-Transaction-Data-Stack
A high-performance Python pipeline for **sampling, normalizing, and storing blockchain Layer-2 transactions** using **Hypersync**, **PyArrow**, and **DuckDB**.
Only displays the .parquet file and data validation (time series charts) here.

------

## Overview

This project implements a complete on-chain data workflow:

1. **Stratified block sampling** across a defined range.
2. **Parallel data gathering** of all transactions per batch.
3. **Normalization and type-safe schema conversion** (via Hypersync).
4. **Efficient columnar storage** in compressed **Parquet** format.
5. **Optional streaming to CSV** for downstream consumption.

The system is optimized for **memory efficiency**, **asynchronous writes**, and **large-scale datasets**.
