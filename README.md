# Market Language Dashboard

Interactive futures macros & stock filter dashboard inspired by "Building the Language".

## Features
- 11 core CME futures macros: NQ, ES, YM, RTY, NKD (Nikkei 225), CL, GC, 6E, 6J, ZN, ZB
- Live delayed quotes via Yahoo Finance (free CORS proxies)
- Stock/ETF filter with regime bias, linked macro, relative strength, and sector
- Click any ticker to open its Finviz chart

## Usage
Open `index.html` in any modern browser. Data refreshes every 60 seconds.

## Notes
- Quotes are delayed (Yahoo Finance free data)
- Relative strength = stock % change − linked macro % change
- Not financial advice
