# AUDUSD 3m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_764_835_rows-blue)](https://getdata.finance/datasets/audusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/audusd)

### -> [**Download the full AUDUSD dataset on getdata.finance**](https://getdata.finance/datasets/audusd)

**AUDUSD 3m OHLCV forex historical data** — ultra high-quality 3m OHLCV for **Australian Dollar / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3m OHLCV** for **Australian Dollar / US Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/audusd) · **1,764,835** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `AUDUSD_3m.csv` (63,207 rows, `2026-03-26` -> `2026-09-25`, 6.18 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/audusd)** — **1,764,835** `3m` rows (full `1m`: 5,263,475), **11 timeframes**, `2012-06-24` -> `2026-09-25`.

## Download sample

**[AUDUSD_3m.csv](https://github.com/getdata-finance/audusd-3m-ohlcv-forex-historical-data/blob/main/AUDUSD_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/audusd-3m-ohlcv-forex-historical-data/main/AUDUSD_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/audusd-3m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/audusd-3m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/audusd-3m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/audusd](https://getdata.finance/datasets/audusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/audusd))** |
|---|--:|---|
| Instrument | Australian Dollar / US Dollar · Forex | Australian Dollar / US Dollar · Forex |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 63,207 | **1,764,835** |
| Size | 6.18 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Period | `2026-03-26` -> `2026-09-25` | `2012-06-24` -> `2026-09-25` |
| File | `AUDUSD_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Coverage report | — | [AUDUSD coverage](https://getdata.finance/coverage/audusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/audusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/audusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUDUSD_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T02:30:00+00:00 | 0.71936 | 0.71943 | 0.71911 | 0.71912 | 482 |
| 2026-03-26T02:33:00+00:00 | 0.71912 | 0.71917 | 0.71861 | 0.71862 | 553 |
| 2026-03-26T02:36:00+00:00 | 0.71862 | 0.7187 | 0.71837 | 0.71858 | 679 |
| 2026-03-26T02:39:00+00:00 | 0.71858 | 0.71876 | 0.71831 | 0.71875 | 567 |
| 2026-03-26T02:42:00+00:00 | 0.71875 | 0.71886 | 0.71867 | 0.71874 | 471 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T20:45:00+00:00 | 0.70262 | 0.70263 | 0.70257 | 0.70262 | 122 |
| 2026-09-25T20:48:00+00:00 | 0.70262 | 0.70265 | 0.70243 | 0.70249 | 172 |
| 2026-09-25T20:51:00+00:00 | 0.70249 | 0.70253 | 0.70247 | 0.70253 | 78 |
| 2026-09-25T20:54:00+00:00 | 0.70253 | 0.70264 | 0.7025 | 0.7025 | 123 |
| 2026-09-25T20:57:00+00:00 | 0.7025 | 0.70257 | 0.70247 | 0.7025 | 589 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AUDUSD_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUDUSD_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AUDUSD_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **AUDUSD** archive on **[getdata.finance](https://getdata.finance/datasets/audusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,764,835** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full AUDUSD dataset on getdata.finance](https://getdata.finance/datasets/audusd)**

---
*GetData · AUDUSD 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/audusd)*
