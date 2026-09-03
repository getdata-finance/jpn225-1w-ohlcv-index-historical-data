# JPN225 1w OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_951_rows-blue)](https://getdata.finance/datasets/jpn225) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/jpn225)

### -> [**Download the full JPN225 dataset on getdata.finance**](https://getdata.finance/datasets/jpn225)

**JPN225 1w OHLCV index historical data** — ultra high-quality 1w OHLCV for **Nikkei 225**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **Nikkei 225** (Index)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/jpn225) · **2,951** `1w` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `JPN225_1w.csv` (8 rows, `2026-07-09` -> `2026-08-27`, 0.59 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/jpn225)** — **2,951** `1w` rows (full `1m`: 5,192,657), **11 timeframes**, `1970-02-12` -> `2026-08-27`.

## Download sample

**[JPN225_1w.csv](https://github.com/getdata-finance/jpn225-1w-ohlcv-index-historical-data/blob/main/JPN225_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/jpn225-1w-ohlcv-index-historical-data/main/JPN225_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/jpn225-1w-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/jpn225-1w-ohlcv-index-historical-data/](https://getdata-finance.github.io/jpn225-1w-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/jpn225](https://getdata.finance/datasets/jpn225)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/jpn225))** |
|---|--:|---|
| Instrument | Nikkei 225 · Index | Nikkei 225 · Index |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1w rows | 8 | **2,951** |
| Size | 0.59 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Period | `2026-07-09` -> `2026-08-27` | `1970-02-12` -> `2026-08-27` |
| File | `JPN225_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Coverage report | — | [JPN225 coverage](https://getdata.finance/coverage/jpn225) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/jpn225)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/jpn225) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`JPN225_1w.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T00:00:00+00:00 | 69037.67 | 69733.1 | 65710.36 | 65932.37 | 935751 |
| 2026-07-16T00:00:00+00:00 | 65932.37 | 67657.22 | 61958.13 | 65446.12 | 1207022 |
| 2026-07-23T00:00:00+00:00 | 65446.12 | 65715.07 | 60521.9 | 63684.12 | 1886710 |
| 2026-07-30T00:00:00+00:00 | 63684.12 | 66816.62 | 62122.59 | 65573.44 | 943354 |
| 2026-08-06T00:00:00+00:00 | 65573.44 | 69550.34 | 64691.65 | 69120.34 | 429184 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-30T00:00:00+00:00 | 63684.12 | 66816.62 | 62122.59 | 65573.44 | 943354 |
| 2026-08-06T00:00:00+00:00 | 65573.44 | 69550.34 | 64691.65 | 69120.34 | 429184 |
| 2026-08-13T00:00:00+00:00 | 69120.34 | 69646.57 | 64889.35 | 65529.35 | 507993 |
| 2026-08-20T00:00:00+00:00 | 65529.35 | 67199.26 | 64613.5 | 65739.25 | 354828 |
| 2026-08-27T00:00:00+00:00 | 65739.25 | 66529.73 | 64226.51 | 64246.99 | 334550 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('JPN225_1w.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('JPN225_1w.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('JPN225_1w.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1W')
print(pf.stats())
```

## Download full data

The complete **JPN225** archive on **[getdata.finance](https://getdata.finance/datasets/jpn225)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,951** rows at `1w`, plus all other timeframes in the same ZIP.

**[-> Get the full JPN225 dataset on getdata.finance](https://getdata.finance/datasets/jpn225)**

---
*GetData · JPN225 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/jpn225)*
