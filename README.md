# EURUSD 2h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_348_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full EURUSD dataset on ork.ad**](https://ork.ad/)

**EURUSD 2h OHLCV Forex historical data** — ultra high-quality 2h OHLCV for **Euro / US Dollar**. 24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 2h OHLCV** for **Euro / US Dollar** (Forex)
- **24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`2h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **2,348** `2h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `2h` sample updated in sync

> **Sample on GitHub** · `EURUSD_2h.csv` (2,328 rows, `2025-10-02` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **2,348** `2h` rows (~0.14 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-10-01` → `2026-07-02`.

## Download sample

**[EURUSD_2h.csv](https://github.com/ork-ad/eurusd-2h-ohlcv-forex-historical-data/blob/main/EURUSD_2h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/eurusd-2h-ohlcv-forex-historical-data/main/EURUSD_2h.csv)) · [GitHub Releases](https://github.com/ork-ad/eurusd-2h-ohlcv-forex-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/eurusd-2h-ohlcv-forex-historical-data/](https://ork-ad.github.io/eurusd-2h-ohlcv-forex-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Euro / US Dollar · Forex | Euro / US Dollar · Forex |
| Timeframes | `2h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 2h rows | 2,328 | **2,348** |
| Size | 0.14 MB | ~0.14 MB |
| Period | `2025-10-02` → `2026-07-02` | `2025-10-01` → `2026-07-02` |
| File | `EURUSD_2h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`2h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `2h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `2h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EURUSD_2h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-02T22:00:00Z | 1.17171 | 1.172602 | 1.171612 | 1.172492 | 3215.0 |
| 2025-10-03T00:00:00Z | 1.172492 | 1.172942 | 1.171642 | 1.172702 | 12926.0 |
| 2025-10-03T02:00:00Z | 1.172702 | 1.172782 | 1.171982 | 1.172632 | 8537.0 |
| 2025-10-03T04:00:00Z | 1.172632 | 1.172812 | 1.171512 | 1.171712 | 9709.0 |
| 2025-10-03T06:00:00Z | 1.171712 | 1.173442 | 1.17161 | 1.173252 | 18123.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T14:00:00Z | 1.14499 | 1.14577 | 1.14329 | 1.14468 | 35406.0 |
| 2026-07-02T16:00:00Z | 1.14468 | 1.14475 | 1.14282 | 1.14299 | 17821.0 |
| 2026-07-02T18:00:00Z | 1.14299 | 1.14363 | 1.14255 | 1.14302 | 11123.0 |
| 2026-07-02T20:00:00Z | 1.14302 | 1.14349 | 1.14275 | 1.14327 | 3427.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('EURUSD_2h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EURUSD_2h.csv', parse_dates=['time'])
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

df = pd.read_csv('EURUSD_2h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='2h')
print(pf.stats())
```

## Download full data

The complete **EURUSD** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **2,348** rows at `2h`, plus all other timeframes in the same ZIP.

**[→ Get the full EURUSD dataset on ork.ad](https://ork.ad/)**

---
*GetData · EURUSD 2h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*