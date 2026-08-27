# Trading Signal Engine v1

Rule-based TradingView Pine Script prototype for research and backtesting.

## Output

- BUY
- SELL
- NO TRADE
- Rule-based score from 0-100
- ATR-based simulated stop-loss and take-profit
- TradingView alert messages
- Strategy Tester support

## Components

- EMA 20 / 50 / 200 trend
- Market structure breakout
- Support / resistance zones
- RSI momentum
- MACD momentum
- Volume confirmation
- Liquidity-style sweep
- Price-action breakout
- ATR volatility filter
- Risk/reward filter through ATR SL and configurable R:R

## Initial test target

XAUUSD, 5-minute chart.

The score is **not** a win probability. There is no guaranteed accuracy or profit. Test across different periods and market conditions before considering any live use.

## TradingView

Open `TradingSignalEngine_v1.pine` in TradingView's Pine Editor and use **Add to chart**. Pine Script v6 supports indicators and strategies, and strategy scripts can be backtested/forward-tested using TradingView's Strategy Tester.

## Current status

V1 prototype. The next development stage should add stronger non-overlapping market-structure/liquidity rules, walk-forward testing, parameter validation, and separate market/timeframe profiles.
