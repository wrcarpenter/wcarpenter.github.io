---
layout: post
author: William Carpenter
tags: [python, fixed-income, pricing]
---
# Z-Spread
This project and source code is available on github [here](https://github.com/wrcarpenter/Z-Spread)

## Introduction 
In fixed income markets, investors rely on various 'spread' measurments to help provide a more informative metric of incremental yield they are receiving vs. a benchmark instrument (ex: Treasury bonds that are often considered to be 'riskless'). This spread would represent compensation for various risks in a given bond that are not in a riskless, benchmark instrument, such as: prepayment risk, credit risk, liquidity risk, etc. Spreads can be readily calculated given a bond cash flow and price and will also give investors a tool to compare relative value between bonds that could have different characteristics. This project focuses on the calculation Z-Spread, which assumes zero-volatility in cash flows and interest rates - it is considered to be a 'static' valutaion tool, but still more informative than a simple yield spread.

## Objectives
Use Treasury data to calculate daily spot rate curves over a given time span. 

Generate mortgage cashflows that have flexibility to handle various prepayment assumptions.

Calculate a bond's Z-Spread for a given cash flow provided a price, or vice-versa

## Procedure
# Obtain U.S. Treasury Par-Yield Data
# Interpolate Semi-Annual Treasury Par Yield Rates
# Bootstrap Semi-Annual Zero Coupon Rate Curves
# Generate a Bond Cash Flow
# Calculate Price Given a Bond Z-Spread
# Calcuate Z-Spread Given a Bond Price 

## Mathematical Background

## Code Examples?

And here is some `inline code`!
Here is a nice code block:
```python
def crr_trinomial_tree(S, K, r, t, T, vol, call, american)
```
## Tables
