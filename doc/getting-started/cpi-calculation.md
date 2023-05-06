---
description: How We Keep Up with CPI
---

# 📈 CPI Calculation

$FLOAT depends on data from [Truflation](https://truflation.com)'s daily Consumer Price Index (CPI) to maintain its value. A specialized oracle from Chainlink immediately records this data on-chain as it becomes public. The inflation rate reported by this oracle is then used to calculate the redemption price of $FLOAT in the system contract. This redemption price changes every second on-chain, reflecting the current inflation rate (or deflation rate, in rare cases). Once every 24 hours, the peg calculation rate is updated using Truflation's daily CPI data.&#x20;

Consequently, the $FLOAT peg is always aligned with the daily inflation rate and is anchored to it by the $FLOAT redemption contract. When traders buy $FLOAT using another asset, such as $ETH, they are effectively speculating that the CPI's purchasing power will appreciate more rapidly over time than will the sold $ETH. Conversely, if traders sell $FLOAT for $ETH, they are taking the position that $ETH's growth will outpace the CPI's inflation rate for the US Dollar.
