# XAUUSD 1m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-6_056_968_rows-blue)](https://getdata.finance/datasets/xauusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xauusd)

### -> [**Download the full XAUUSD dataset on getdata.finance**](https://getdata.finance/datasets/xauusd)

**XAUUSD 1m OHLCV metals historical data** — ultra high-quality 1m OHLCV for **Gold / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **Gold / US Dollar** (Metals)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/xauusd) · **6,056,968** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `XAUUSD_1m.csv` (179,662 rows, `2026-03-26` -> `2026-09-25`, 15.21 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/xauusd)** — **6,056,968** `1m` rows (full `1m`: 5,887,627), **11 timeframes**, `2009-02-24` -> `2026-09-25`.

## Download sample

**[XAUUSD_1m.csv](https://github.com/getdata-finance/xauusd-1m-ohlcv-metals-historical-data/blob/main/XAUUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xauusd-1m-ohlcv-metals-historical-data/main/XAUUSD_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/xauusd-1m-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xauusd-1m-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xauusd-1m-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xauusd](https://getdata.finance/datasets/xauusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xauusd))** |
|---|--:|---|
| Instrument | Gold / US Dollar · Metals | Gold / US Dollar · Metals |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 179,662 | **6,056,968** |
| Size | 15.21 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Period | `2026-03-26` -> `2026-09-25` | `2009-02-24` -> `2026-09-25` |
| File | `XAUUSD_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Coverage report | — | [XAUUSD coverage](https://getdata.finance/coverage/xauusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xauusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/xauusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAUUSD_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T02:28:00+00:00 | 4617.45 | 4618.25 | 4616.04 | 4617.53 | 604 |
| 2026-03-26T02:29:00+00:00 | 4617.53 | 4618.14 | 4616.42 | 4617.23 | 388 |
| 2026-03-26T02:30:00+00:00 | 4617.23 | 4618.83 | 4616 | 4618.34 | 1279 |
| 2026-03-26T02:31:00+00:00 | 4618.34 | 4619.89 | 4616.93 | 4618.58 | 886 |
| 2026-03-26T02:32:00+00:00 | 4618.58 | 4619.11 | 4617.04 | 4617.32 | 524 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T20:40:00+00:00 | 4285.69 | 4285.98 | 4285.06 | 4285.15 | 91 |
| 2026-09-25T20:41:00+00:00 | 4285.15 | 4285.45 | 4284.95 | 4285.45 | 116 |
| 2026-09-25T20:42:00+00:00 | 4285.45 | 4286 | 4284.72 | 4284.73 | 131 |
| 2026-09-25T20:43:00+00:00 | 4284.73 | 4285.3 | 4284.73 | 4285.16 | 68 |
| 2026-09-25T20:44:00+00:00 | 4285.16 | 4285.2 | 4284.52 | 4284.76 | 71 |

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

df = pd.read_csv('XAUUSD_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAUUSD_1m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('XAUUSD_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **XAUUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xauusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **6,056,968** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full XAUUSD dataset on getdata.finance](https://getdata.finance/datasets/xauusd)**

---
*GetData · XAUUSD 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xauusd)*
