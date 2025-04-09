# A4-PI2-Team259
Exploring the dynamic between oil prices and petro-currencies (RUB &amp; NOK), with historical data, visualizations, and contextual insights from major geopolitical events.


# PetroDollar: Exploring Petro-Currency Dynamics

This notebook investigates the evolving relationship between global oil prices and the exchange rates of two key petroleum-exporting countries: Russia (RUB) and Norway (NOK). We use time series data from 2015 to 2024 to understand how these so-called "petro-currencies" respond to fluctuations in oil prices, especially in the context of major geopolitical events.

## Context & Motivation

Oil-exporting economies are often financially dependent on crude oil revenues. This dependency creates a tight link between their currency values and global oil price movements. Our motivation was to explore:
- How sensitive these currencies are to Brent crude oil price movements.
- Whether this sensitivity changes under geopolitical stress, such as during the 2022 invasion of Ukraine.
- How investor behavior (e.g., "safe haven" dynamics or risk aversion) might influence currencies like the NOK in contrast to the RUB.

By focusing on RUB and NOK, we contrast an emerging economy under sanctions with a developed, stable economy, both exposed to oil revenues.

## Methods & Tools

The analysis was performed using Python, mainly relying on:
- `yfinance` to extract historical market data (Brent Crude, USD/RUB, USD/NOK).
- `pandas` for data processing and structuring.
- `plotly` for interactive time series visualization.
- Manual annotation of events for better contextual understanding.

We highlight key historical episodes (e.g., oil price crashes, global lockdowns, war in Ukraine) directly on the charts, to show how market perception and real-world events intertwine with currency behaviors.

## Outputs

The result is a visual, time-based story that highlights:
- The persistent correlation between oil and petro-currencies.
- A divergence in behavior between RUB and NOK during times of geopolitical instability.
- The nuanced role of oil as both a commodity and an economic signal in foreign exchange markets.

