# Pine Script Indicator Suite

A collection of TradingView Pine Script indicators for market visualization and learning purposes.

## Note

**These indicators are for educational and visualization purposes only. They do not constitute financial advice.**

## Included Indicators

- **fractals.pine** - Detects fractal highs and lows using configurable left bars. Displays as triangles or circles on the chart.

- **liquidity-swings.pine** - Tracks fractal-based swing highs and lows. Shows liquidity levels with lines that turn dashed when broken by price close.

- **quarterly-cycles.pine** - Draws previous day, 6-hour, 90-minute, and 22.5-minute cycle high/low lines as horizontal levels. Lines extend until broken, then become dashed.

- **fvgs.pine** - Plots Fair Value Gap boxes (SIBI/BISI) based on 3-candle patterns. Shows bullish and bullish FVG zones with configurable colors.

- **ict-macros.pine** - Highlights ICT-style timed macros (last 10 and first 10 minutes of each hourly candle). Displays in a separate pane below the chart.

- **true-opens.pine** - Draws horizontal rays at true day open (midnight New York) and 8:30 AM New York open with labels.

- **vertical-sessions.pine** - Plots vertical dotted lines at configurable session start and end times. Supports up to 6 sessions with New York timezone option.

## How to Use in TradingView

1. Open the [script file](/scripts) you want to use
2. Copy the entire code
3. In TradingView, open the Pine Script editor
4. Paste the code
5. Click "Add to chart"

## Requirements

- TradingView account with Pine Script v6 support
- Each indicator requires specific chart permissions (overlay vs. separate pane)

## License

Mozilla Public License 2.0