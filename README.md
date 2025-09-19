# Arbitrage Bet Calculator

Universal Arbitrage Calculator for 2, 3, and 4-way betting markets.

## Features

- **Arbitrage Calculation**: Detects arbitrage opportunities for 2-way, 3-way, and experimental 4-way markets.
- **Stake Splitting**: Automatically splits your total stake across all outcomes to guarantee a profit if arbitrage exists.
- **Implied Probability & Overround**: Calculates and displays implied probability sum and overround percentage for entered odds.
- **Dynamic UI**: Input fields adjust based on the number of outcomes. Includes quick example selector.
- **Result Display**: Shows individual stakes, expected returns, guaranteed payout, profit, and ROI.
- **Calculation History**: Save, view, clear, and export calculation history as CSV.
- **Responsive & Accessible**: Works on desktop and mobile, with accessible modals and notifications.
- **About & Help**: Built-in about modal explaining arbitrage and usage.

## About

This tool checks whether a set of decimal odds across 2, 3, or 4 mutually exclusive outcomes contains an arbitrage opportunity. It calculates the implied probabilities (`1/odds`), sums those probabilities, and—if the sum is less than 1—shows a stake split that (in theory) returns your capital plus a guaranteed small profit regardless of which outcome wins.

### Example

**Football (3-way):**

```
Home Win: 2.10 | Draw: 3.40 | Away Win: 3.60
If 1/2.10 + 1/3.40 + 1/3.60 < 1, you can split your stake across the three bets to lock in profit.
```

**Tennis (2-way):**

```
Player A: 1.95 | Player B: 2.05
Use 2-way mode for these markets.
```

**4-way (experimental):**

Some rare markets with four mutually exclusive outcomes (e.g., set-score markets).

### Caveats

- Execution risk, stake limits, commission, voided markets, and price movement can all break an arbitrage in practice.
- Always verify settlement rules and max stakes at each bookmaker.

## Disclaimer

It is possible for both outcomes to fail as you can't always be 100% right on sports betting. **Bet wisely.**