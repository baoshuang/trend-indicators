Implementing trend indicators in kdb+
=====================================

Companion code to the [eponymous Kx white paper](https://code.kx/com/q/wp/trend-indicators/)


`GraphicGrammerPLotsWP.q`

: Contains all code used in Analyst to graph statistics.

`crypto.py`

: Python code used to connect to cryptocurrency feeds and extract trade and quote information, which is then passed to ticker plant.

cryptoFuncs.q

: Contains the q code to generate all statistics/oscillators and indicators.

The rest of the files are standard tickerplant, realtime database, and end-of-day code.

The paper describes using kdb+ to produce trade analytics – indicators and oscillators traders commonly use to trigger buy/sell signals and clarify their picture of the market.