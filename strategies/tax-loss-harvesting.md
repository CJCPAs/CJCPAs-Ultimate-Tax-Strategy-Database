# Tax Loss Harvesting

## Overview

Tax loss harvesting is the practice of selling investments at a loss to offset capital gains and reduce taxable income. By strategically realizing losses while maintaining market exposure through similar (but not substantially identical) investments, investors can reduce their current tax liability while preserving their long-term investment strategy. Done systematically, this can add significant after-tax value over an investment lifetime.

## Key Benefits

- Offset capital gains dollar-for-dollar
- Deduct up to $3,000 of net losses against ordinary income annually
- Carry forward unused losses indefinitely
- Maintain market exposure while realizing tax benefit
- Potentially increase after-tax returns by 0.5-1%+ annually
- Convert short-term gains to long-term treatment (timing strategy)
- Reduce taxable estate

## How Tax Loss Harvesting Works

### Basic Mechanics

```
┌──────────────────────────────────────────────────────────────────┐
│                    Tax Loss Harvesting Process                    │
├──────────────────────────────────────────────────────────────────┤
│                                                                   │
│  1. Identify investment with unrealized loss                     │
│     └─► Stock A: Bought $100,000, now worth $70,000 = $30K loss  │
│                                                                   │
│  2. Sell investment to realize loss                              │
│     └─► Sell Stock A for $70,000, realize $30,000 loss           │
│                                                                   │
│  3. Immediately purchase similar (not identical) investment       │
│     └─► Buy Stock B or ETF covering same sector: $70,000         │
│                                                                   │
│  4. Use loss to offset gains or income                           │
│     └─► $30,000 loss offsets $30,000 in gains = $0 net gain      │
│                                                                   │
└──────────────────────────────────────────────────────────────────┘
```

### Tax Offset Rules

**Netting Order:**
1. Short-term losses offset short-term gains first
2. Long-term losses offset long-term gains first
3. Net short-term offset against net long-term
4. Net loss up to $3,000 offsets ordinary income
5. Remaining losses carry forward

**Example:**
| Type | Gains | Losses | Net |
|------|-------|--------|-----|
| Short-term | $20,000 | ($35,000) | ($15,000) |
| Long-term | $50,000 | ($10,000) | $40,000 |
| **Net** | | | **$25,000 LTCG** |

$15,000 ST loss offsets $15,000 of LT gain
Remaining $25,000 taxed at LTCG rates

### Tax Value of Losses

| Loss Type | Offsetting | Tax Rate Saved | Value per $1,000 |
|-----------|------------|----------------|------------------|
| ST loss vs ST gain | Short-term gains | 37% | $370 |
| ST loss vs LT gain | Long-term gains | 23.8% | $238 |
| LT loss vs LT gain | Long-term gains | 23.8% | $238 |
| LT loss vs ST gain | Short-term gains | 37% | $370 |
| Any loss vs ordinary | Up to $3,000/year | 37% | $370 |

## The Wash Sale Rule

### What Is a Wash Sale?

A wash sale occurs when you sell a security at a loss and buy a "substantially identical" security within 30 days before or after the sale. The loss is **disallowed** and added to the basis of the new shares.

### The 61-Day Window

```
         30 days before        Sale        30 days after
    ◄─────────────────────┬───────────┬─────────────────────►
                          │   LOSS    │
                          │   SALE    │
    │                     │           │                     │
    └─────────────────────┴───────────┴─────────────────────┘
                    WASH SALE WINDOW

    Cannot buy substantially identical security during this period
```

### Substantially Identical Securities

| Scenario | Wash Sale? |
|----------|------------|
| Sell Apple, buy Apple | Yes |
| Sell Apple, buy Microsoft | No |
| Sell S&P 500 ETF (SPY), buy S&P 500 ETF (IVV) | Likely Yes |
| Sell S&P 500 ETF, buy Total Market ETF | Likely No |
| Sell S&P 500 ETF, buy NASDAQ ETF | No |
| Sell stock, buy call option on same stock | Yes |
| Sell bond fund, buy similar bond fund | Case-by-case |

### Wash Sale Consequences

**If triggered:**
- Loss disallowed in current year
- Disallowed loss added to basis of new shares
- Holding period of old shares carries over
- Loss is deferred, not permanently lost

**Example:**
- Buy 100 shares at $100 = $10,000
- Sell at $70 = $7,000 (would be $3,000 loss)
- Buy 100 shares at $70 within 30 days
- Wash sale: $3,000 loss disallowed
- New basis: $70 + $30 = $100
- Loss recovered when new shares sold

## Implementation Strategies

### Strategy 1: Year-End Harvesting

**Approach:**
- Review portfolio in November/December
- Identify positions with unrealized losses
- Harvest losses to offset realized gains
- Reinvest in similar (not identical) investments

**Checklist:**
- [ ] Calculate YTD realized gains
- [ ] Identify all unrealized losses
- [ ] Prioritize short-term losses (higher value)
- [ ] Select replacement investments
- [ ] Execute trades before year-end
- [ ] Document for tax reporting

### Strategy 2: Continuous/Automated Harvesting

**Approach:**
- Monitor portfolio daily or weekly
- Harvest losses when threshold met (e.g., 5% decline)
- Automated through robo-advisors or systematic process
- Reinvest immediately in similar investments

**Benefits:**
- Captures losses throughout the year
- More opportunities than year-end only
- Studies show 0.5-1%+ annual tax alpha

**Example Triggers:**
| Asset Class | Harvest Threshold |
|-------------|-------------------|
| Individual stocks | 5-10% loss |
| Broad ETFs | 3-5% loss |
| Sector funds | 5-7% loss |

### Strategy 3: Gain/Loss Matching

**Approach:**
- When realizing gains, simultaneously harvest losses
- Match short-term gains with short-term losses (higher value)
- Match long-term gains with long-term losses

**Example:**
| Transaction | Type | Amount |
|-------------|------|--------|
| Sell appreciated stock | ST gain | +$50,000 |
| Harvest loss position | ST loss | -$50,000 |
| Net taxable | | $0 |
| Tax saved (37%) | | $18,500 |

### Strategy 4: Specific Lot Identification

**Approach:**
- Identify specific high-cost lots for sale
- Versus selling FIFO (first in, first out)
- Maximize losses or minimize gains

**Example:**
| Lot | Purchase Date | Cost | Current Value | Gain/Loss |
|-----|---------------|------|---------------|-----------|
| Lot 1 | 1/15/2023 | $50,000 | $45,000 | ($5,000) |
| Lot 2 | 6/15/2023 | $60,000 | $45,000 | ($15,000) |
| Lot 3 | 1/15/2024 | $40,000 | $45,000 | $5,000 |

**Optimal for loss harvesting**: Sell Lot 2 specifically

### Strategy 5: Asset Location Optimization

**Principle**: Hold tax-inefficient assets in tax-advantaged accounts

**Tax Loss Harvesting Fit:**
- Keep harvestable assets in taxable accounts
- Bonds, REITs in tax-advantaged accounts
- Individual stocks (harvestable) in taxable accounts
- Index funds (for replacement) in taxable accounts

## Requirements

### Documentation Requirements
- Maintain purchase records (date, price, shares)
- Track each tax lot separately
- Document replacement investments
- Keep wash sale calculations
- Retain for at least 7 years

### Form 8949 Reporting
- Report all sales on Form 8949
- Categorize short-term vs. long-term
- Include wash sale adjustments
- Flow to Schedule D

### Basis Tracking
- Know cost basis method (specific ID vs. FIFO vs. average)
- Track adjustments from wash sales
- Coordinate with broker 1099-B

## Client Fit Criteria

### Ideal Candidates
- High-income taxpayers (benefit from high rates)
- Those with realized capital gains
- Investors with taxable accounts of $100,000+
- Long time horizon (more harvesting opportunities)
- Those using index-based investing (easy replacement)
- Business owners with concentrated positions

### Best Account Types
- Individual/joint taxable brokerage accounts
- Trust accounts
- NOT tax-advantaged accounts (IRA, 401k)—no benefit

### When Most Valuable
- Years with high capital gains
- Market downturns (more loss opportunities)
- Volatility (creates more opportunities)
- When rebalancing portfolio
- When exiting concentrated positions

## Risks & Considerations

### Wash Sale Risk
- Careful coordination across accounts
- Spouse accounts count
- IRA purchases can trigger wash sale
- Dividend reinvestment may trigger wash sale

### Tracking Complexity
- Multiple lots to track
- Adjusted basis calculations
- Multiple replacement investments
- Software or professional help often needed

### Transaction Costs
- Trading commissions (mostly zero now)
- Bid-ask spreads
- Potential market impact (large positions)

### Replacement Investment Risk
- New investment may not perform identically
- Tracking error during replacement period
- May miss dividends during switch

### Long-Term Tax Deferral Trade-off
- Harvesting lowers basis of replacement
- Future sales have larger gains
- But time value of tax savings usually wins
- Avoid "harvesting to harvest" without strategy

## Case Study

### Scenario
David has a $2,000,000 taxable portfolio and the following situation in December:

**YTD Realized Gains:**
- Short-term gains: $100,000
- Long-term gains: $150,000

**Unrealized Positions:**
| Position | Cost Basis | Current Value | Unrealized |
|----------|------------|---------------|------------|
| Growth Fund | $200,000 | $150,000 | ($50,000) |
| Tech ETF | $300,000 | $250,000 | ($50,000) |
| Value Stock A | $100,000 | $80,000 | ($20,000) |
| Value Stock B | $150,000 | $180,000 | $30,000 |
| Bond Fund | $500,000 | $480,000 | ($20,000) |

### Tax Loss Harvesting Strategy

**Step 1: Identify harvestable losses**
- Growth Fund: $50,000 loss (LT)
- Tech ETF: $50,000 loss (ST - held < 1 year)
- Value Stock A: $20,000 loss (LT)
- Bond Fund: $20,000 loss (LT)
- Total potential: $140,000

**Step 2: Match against gains**
| Gains | Losses Harvested | Net |
|-------|------------------|-----|
| $100,000 ST | $50,000 ST (Tech ETF) | $50,000 ST |
| $150,000 LT | $90,000 LT (Growth + Value A + Bond) | $60,000 LT |

**Step 3: Calculate tax savings**
| Item | Amount | Tax Rate | Tax |
|------|--------|----------|-----|
| Without harvesting: | | | |
| ST gains | $100,000 | 37% | $37,000 |
| LT gains | $150,000 | 23.8% | $35,700 |
| **Total tax** | | | **$72,700** |
| | | | |
| With harvesting: | | | |
| ST gains (net) | $50,000 | 37% | $18,500 |
| LT gains (net) | $60,000 | 23.8% | $14,280 |
| **Total tax** | | | **$32,780** |
| | | | |
| **Tax savings** | | | **$39,920** |

**Step 4: Reinvest in replacement investments**
| Sold | Replacement | Notes |
|------|-------------|-------|
| Growth Fund (SPY tracking) | Total Market ETF (VTI) | Different index, no wash sale |
| Tech ETF (QQQ) | Different Tech ETF or individual stocks | Careful on substantial identity |
| Value Stock A | Similar value stock B | Different company |
| Bond Fund | Different duration bond fund | Different composition |

### Long-Term Impact

**Assuming continued annual harvesting:**
- Annual tax savings: $20,000-40,000
- 20-year benefit: $400,000-800,000 in tax savings
- Plus compounding of reinvested tax savings

## Tax Loss Harvesting with Specific Situations

### RSU/Stock Option Integration
- Large vesting creates short-term gains
- Harvest losses to offset
- Coordinate timing with vesting schedule

### Business Sale/Exit
- Capital gains from business sale
- Pre-harvest losses in anticipation
- May need to harvest year before (carryforward)

### Charitable Giving Coordination
- Don't donate loss positions (no double benefit)
- Donate appreciated positions
- Sell loss positions to harvest

### Estate Planning
- Losses don't get stepped-up basis benefit
- May want to harvest before death
- Carryforward losses are lost at death

## Key Tax Code References

- **IRC Section 1091**: Wash sale rules
- **IRC Section 1211**: Limitation on capital losses
- **IRC Section 1212**: Capital loss carryovers
- **IRC Section 1001**: Determination of gain or loss
- **IRC Section 1223**: Holding period
- **Treas. Reg. 1.1091-1**: Wash sale regulations

## Related Strategies

- [Roth Conversions](roth-conversions.md)
- [Charitable Strategies](charitable-strategies.md)
- [RSUs](rsus.md)
- [Exit Planning](exit-planning.md)
- [Opportunity Zones](opportunity-zones.md)

---

*Last Updated: 2025*
