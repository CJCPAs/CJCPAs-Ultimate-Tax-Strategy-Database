# Alternative Minimum Tax (AMT) Planning

## Overview

The Alternative Minimum Tax (AMT) is a parallel tax system designed to ensure high-income taxpayers pay at least a minimum amount of tax by limiting certain deductions and preferences. While the Tax Cuts and Jobs Act (TCJA) of 2017 significantly reduced the number of taxpayers subject to AMT, it remains a concern for certain situations, particularly those involving incentive stock options (ISOs), large state tax deductions, and significant itemized deductions.

## Key Concepts

### How AMT Works

```
┌─────────────────────────────────────────────────────────────┐
│                    Regular Tax Calculation                   │
│  Gross Income - Deductions = Taxable Income                 │
│  Taxable Income × Tax Rates = Regular Tax                   │
└─────────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│                      AMT Calculation                         │
│  Regular Taxable Income                                      │
│  + AMT Preference Items                                      │
│  + AMT Adjustments                                          │
│  - AMT Exemption                                            │
│  = AMT Income (AMTI)                                        │
│  × AMT Rates (26%/28%)                                      │
│  = Tentative Minimum Tax                                    │
└─────────────────────────────────────────────────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│                    TAX OWED = Greater of:                    │
│              Regular Tax OR Tentative Minimum Tax            │
└─────────────────────────────────────────────────────────────┘
```

### AMT vs. Regular Tax Comparison

| Feature | Regular Tax | AMT |
|---------|-------------|-----|
| Tax rates | 10%-37% | 26%-28% |
| Standard deduction | Yes | No |
| Personal exemptions | No longer applicable | No |
| State/local tax deduction | $10,000 cap | Not allowed |
| Mortgage interest | Acquisition debt only | Same |
| Medical expenses | 7.5% AGI floor | 7.5% AGI floor |
| Miscellaneous deductions | Not allowed | Not allowed |
| ISO exercise spread | Not taxable | Preference item |

## AMT Exemption and Phase-Out (2024)

### Exemption Amounts

| Filing Status | Exemption | Phase-Out Begins | Exemption Eliminated |
|---------------|-----------|------------------|---------------------|
| Single | $85,700 | $609,350 | $952,150 |
| MFJ | $133,300 | $1,218,700 | $1,751,900 |
| MFS | $66,650 | $609,350 | $875,950 |

### Phase-Out Mechanics
- Exemption reduced by 25 cents for each $1 over threshold
- Creates effective marginal rates of 32.5% and 35%
- Complete phase-out at elimination amount

## Common AMT Triggers

### 1. Incentive Stock Option (ISO) Exercise

**The #1 AMT trigger for many taxpayers**

| Item | Regular Tax | AMT |
|------|-------------|-----|
| ISO Exercise spread | Not taxable | Preference item |
| Result | May owe no regular tax | May owe significant AMT |

**Example:**
- Exercise 10,000 ISOs
- Strike price: $10
- FMV at exercise: $50
- Spread: $40 × 10,000 = $400,000
- AMT preference: $400,000
- Potential AMT: $104,000-$112,000

### 2. State and Local Tax (SALT) Deduction

**Regular tax**: $10,000 cap (TCJA)
**AMT**: Not deductible at all

For high SALT taxpayers, the $10,000 cap reduced AMT exposure (both systems now similar treatment).

### 3. Large Itemized Deductions

**Items that can trigger AMT:**
- Investment interest expense
- Certain depreciation methods
- Private activity bond interest
- Tax-exempt interest from certain bonds

### 4. Long-Term Capital Gains

**Not a preference item, but:**
- Can push AMT income into phase-out range
- May trigger AMT by reducing regular tax below AMT

### 5. Miscellaneous Situations

- Large exercised employee stock options
- Passive activity losses
- Net operating loss limitations
- Accelerated depreciation
- Certain tax shelter investments

## Requirements

### Form 6251 Filing

Required if:
- Claiming AMT adjustment or preference items
- AMT liability exists
- Claiming AMT credit
- Certain ISO exercises

### AMT Credit Tracking

**Minimum Tax Credit (MTC):**
- AMT from "timing" differences creates credit
- Credit used when regular tax exceeds AMT in future years
- Can carry forward indefinitely
- ISOs are primary source of AMT credit

## Client Fit Criteria

### Who Needs AMT Planning?

| Situation | AMT Risk |
|-----------|----------|
| ISO holders planning exercise | High |
| High SALT taxpayers (before TCJA) | Reduced post-TCJA |
| Private activity bond investors | Moderate |
| Large investment interest expense | Moderate |
| Tax shelter participants | High |
| High income + large capital gains | Moderate |

### Post-TCJA Reality

**AMT is less common because:**
- Higher exemptions ($133,300 MFJ vs. old $86,200)
- Higher phase-out thresholds
- SALT cap already limits deduction for regular tax
- No personal exemptions to lose

**But still affects:**
- ISO exercisers
- Very high income taxpayers
- Those with specific preferences

## Planning Strategies

### Strategy 1: ISO Exercise Optimization

**Goal**: Exercise ISOs without triggering excessive AMT

**AMT Crossover Calculation:**
1. Calculate regular tax without ISOs
2. Calculate AMT without ISO preference
3. Difference = "AMT cushion"
4. Exercise ISOs up to cushion amount

**Example:**
| Item | Amount |
|------|--------|
| Regular tax (without ISO) | $150,000 |
| AMT (without ISO preference) | $120,000 |
| AMT cushion | $30,000 |
| Can exercise ISOs with spread of | ~$115,000 |
| (Generates ~$30,000 AMT) | |

**Multi-Year Strategy:**
- Spread ISO exercises across years
- Stay within AMT cushion each year
- Avoid large one-time AMT hit
- May require modeling multiple scenarios

### Strategy 2: AMT Credit Recovery Planning

**If you've paid AMT, you may have credits to recover**

**How MTC Works:**
| Year | Regular Tax | AMT | Tax Paid | Credit Generated |
|------|-------------|-----|----------|------------------|
| 2024 | $100,000 | $150,000 | $150,000 | $50,000 MTC |
| 2025 | $150,000 | $120,000 | $150,000 | Use $30,000 MTC |
| 2026 | $180,000 | $130,000 | $160,000 | Use $20,000 MTC |

**Accelerating Credit Recovery:**
- Realize more regular tax income
- Reduce AMT adjustments
- Plan timing of preference items
- Consider Roth conversions (increase regular tax, use MTC)

### Strategy 3: Income Timing

**Accelerate or defer income based on AMT situation:**

| Scenario | Strategy |
|----------|----------|
| Deep in AMT this year | Defer income to next year |
| Close to AMT threshold | May accelerate income (pay at regular rates) |
| Large ISO exercise planned | Defer other income if possible |
| Have MTC to use | Accelerate income to use credits |

### Strategy 4: Deduction Timing

**Some deductions have different AMT/regular treatment:**

| Deduction | Regular Tax | AMT | Strategy |
|-----------|-------------|-----|----------|
| SALT | $10,000 cap | $0 | No timing benefit |
| Charitable | Deductible | Deductible | Neutral |
| Mortgage interest | Deductible | Limited | Time carefully |
| Investment interest | Deductible | Deductible | Neutral |

### Strategy 5: Investment Selection

**Avoid AMT preference items in taxable accounts:**
- Private activity bonds (interest is AMT preference)
- Tax shelter investments
- Certain oil/gas investments with IDCs

**Consider instead:**
- Regular municipal bonds (AMT-free)
- Index funds (tax-efficient)
- Growth stocks (defer gains)

### Strategy 6: Same-Day Sale for ISOs

**If AMT is concern, consider disqualifying disposition:**

| Approach | Tax Treatment |
|----------|---------------|
| Exercise and hold | AMT on spread |
| Exercise and sell same day | Ordinary income on spread, no AMT |

**When Same-Day Makes Sense:**
- Very large spread relative to income
- Uncertainty about stock performance
- Need liquidity
- Cannot afford AMT payment

## AMT Calculation Example

### Scenario
Jennifer and Mike have the following situation:
- Salary: $400,000
- Long-term capital gains: $100,000
- State/local taxes: $50,000
- Mortgage interest: $30,000
- Jennifer exercises ISOs: $200,000 spread

### Regular Tax Calculation

| Item | Amount |
|------|--------|
| Salary | $400,000 |
| Capital gains | $100,000 |
| AGI | $500,000 |
| SALT (capped) | ($10,000) |
| Mortgage interest | ($30,000) |
| Taxable income | $460,000 |
| Regular tax | ~$108,000 |

### AMT Calculation

| Item | Amount |
|------|--------|
| Regular taxable income | $460,000 |
| Add back: SALT deduction | $10,000 |
| Add: ISO spread | $200,000 |
| AMTI | $670,000 |
| Less: Exemption (phase-out applies) | ~$67,000 |
| AMT taxable income | $603,000 |
| Tentative minimum tax (28%) | ~$168,840 |

### Tax Owed
- Regular tax: $108,000
- Tentative AMT: $168,840
- **AMT owed: $168,840 - $108,000 = $60,840 additional**

### Minimum Tax Credit
- AMT from ISO (timing item): $60,840
- MTC generated: $60,840
- Can use in future years when regular tax > AMT

## Risks & Considerations

### AMT Traps

**ISO Exercise Timing:**
- Exercising too many ISOs in one year
- Not modeling AMT before exercising
- Market decline after exercise (still owe AMT)

**Year-End Planning:**
- December ISO exercises may trigger AMT
- January exercise may defer to next tax year
- Consider implications carefully

### Stock Price Decline After ISO Exercise

**The "AMT Trap":**
- Exercise ISOs when stock at $100
- Pay AMT on $100 value
- Stock drops to $30
- Still owe AMT, but stock worth much less
- **No way to recover AMT (credit helps long-term)**

### Planning Complexity

**AMT calculations require:**
- Projection of all income items
- Understanding of AMT adjustments
- Modeling of exemption phase-out
- Coordination with state AMT (if applicable)

## State AMT Considerations

**States with AMT:**
- California (7% flat rate)
- Connecticut
- Colorado
- Iowa
- Minnesota
- Wisconsin

**Planning implications:**
- State AMT may be triggered independently
- ISO exercises affect state AMT
- Coordinate federal and state planning

## Case Study

### Scenario
Robert, single, has the following:
- Base salary: $300,000
- Has 50,000 ISOs: Strike $10, current FMV $30
- Wants to exercise before IPO

### Analysis: Full Exercise

**If exercises all 50,000 ISOs:**
- Spread: $20 × 50,000 = $1,000,000
- AMT preference: $1,000,000
- Estimated AMT: ~$280,000
- Risk: If stock drops to $15, owes $280K AMT but only $750K stock value

### Recommended Strategy: Phased Exercise

**Year 1:** Exercise 15,000 shares
- Spread: $300,000
- AMT generated: ~$80,000
- MTC created: ~$80,000

**Year 2:** Exercise 15,000 shares
- Spread: $300,000 (assuming same price)
- AMT generated: ~$80,000

**Year 3:** Exercise remaining 20,000 shares
- Timing based on IPO status
- If IPO happens, may do disqualifying disposition

### Benefit of Phased Approach
- Lower annual AMT payments
- Reduce concentration risk
- Flexibility to adjust based on stock performance
- Begin MTC recovery earlier

## Key Tax Code References

- **IRC Section 55**: Alternative minimum tax imposed
- **IRC Section 56**: Adjustments to taxable income
- **IRC Section 57**: Items of tax preference
- **IRC Section 58**: Denial of certain losses
- **IRC Section 59**: Other definitions and special rules
- **IRC Section 53**: Minimum tax credit
- **Form 6251**: Alternative Minimum Tax—Individuals

## Related Strategies

- [Stock Options](stock-options.md)
- [Section 83(b) Elections](section-83b-elections.md)
- [Roth Conversions](roth-conversions.md)
- [Tax Loss Harvesting](tax-loss-harvesting.md)
- [Charitable Strategies](charitable-strategies.md)

---

*Last Updated: 2025*
