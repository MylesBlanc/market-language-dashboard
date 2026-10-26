# Core Futures Dashboard

Interactive futures indices & stock filter dashboard.

## Features
- 11 core CME futures indices: NQ, ES, YM, RTY, NKD (Nikkei 225), CL, GC, 6E, 6J, ZN, ZB
- Live delayed quotes via Yahoo Finance (free CORS proxies)
- Stock/ETF filter with regime bias, linked index, relative strength, and sector
- Click any ticker to open its Finviz chart

## Usage
Open `index.html` in any modern browser. Data refreshes every 60 seconds.

## Notes
- Quotes are delayed (Yahoo Finance free data)
- Relative strength = stock % change − linked index % change
- Not financial advice
