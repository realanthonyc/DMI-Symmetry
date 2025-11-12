# DMI Symmetry (DMIS) for TradingView

© realanthonyc  
https://x.com/anthonycxc | https://www.tradingview.com/u/realanthonyc

Pine Script® v6

## Overview
DMI Symmetry (DMIS) reframes the classic Directional Movement Index into an adaptive momentum read that highlights whether total directional pressure is balanced or skewed through time. DMIS delivers an ideal real-time visualization of long-versus-short pressure. The script auto-tunes DI lengths per timeframe so shorter charts stay reactive while higher timeframes stay stable.

## What the script does
- Applies separate DI length presets for intraday, swing, and higher timeframes with a fallback for exotic intervals.
- Adds optional EMA smoothing to +DI/-DI and the Symmetry Line to control noise versus responsiveness.
- Builds a Symmetry Line with a configurable reference band to show when overall directional activity stretches away from its mean.
- Tracks ADX in the background and offers 2-bar confirmation alerts for bullish and bearish DI crosses.

## What’s on the chart
- +DI and -DI lines with user-defined smoothing.
- Symmetry Line plus shaded reference band highlighting balanced versus imbalanced momentum.
- Optional ADX area (hidden by default) backing the directional consensus.

## Changelog
Please refer to the release notes.
