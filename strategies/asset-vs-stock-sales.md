# Asset vs. Stock Sales (Section 338 Elections)

## Overview

When selling a business, one of the most important tax decisions is whether to structure the transaction as an asset sale or a stock sale. This choice significantly impacts both the buyer and seller's tax consequences. For C-corporations, Section 338 elections can allow parties to achieve asset sale treatment while legally selling stock. Understanding these options is critical for optimizing after-tax proceeds in any M&A transaction.

## Effective Dates & Key Law Changes

| Provision | Current Law | 2026 and Beyond |
|-----------|-------------|-----------------|
| Corporate Tax Rate | 21% | 21% (no change scheduled) |
| Capital Gains Rate (Individual) | 0%/15%/20% + 3.8% NIIT | Same |
| Ordinary Income Rate (max) | 37% | 37% (TCJA rates permanent - OBBBA 2025) |
| QSBS Exclusion (Section 1202) | 100% | 100% (permanent) |
| Section 338(h)(10) | Available | No change expected |
| Section 336(e) | Available | No change expected |
| Bonus Depreciation | 100% (permanent - OBBBA 2025) | 100% (permanent) |

## Asset Sale vs. Stock Sale Basics

### Comparison Overview

```
┌─────────────────────────────────────────────────────────────────┐
│               ASSET SALE VS. STOCK SALE COMPARISON               │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  ASSET SALE                         STOCK SALE                   │
│  ──────────                         ──────────                   │
│                                                                  │
│  What's sold:                       What's sold:                 │
│  • Individual assets                • Ownership interests        │
│  • Buyer picks which assets         • All assets AND liabilities │
│  • Liabilities usually stay         • Entity continues           │
│                                                                  │
│  Buyer's basis:                     Buyer's basis:               │
│  • FMV (stepped up)                 • Carryover (no step-up)     │
│  • New depreciation                 • Old depreciation continues │
│                                                                  │
│  Seller's tax:                      Seller's tax:                │
│  • Corporate level (if C-Corp)      • Shareholder level only     │
│  • Character depends on asset       • Usually capital gain       │
│  • Ordinary recapture common        • More favorable             │
│                                                                  │
│  BUYER PREFERS: Asset Sale          SELLER PREFERS: Stock Sale   │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

### Tax Treatment Summary

| Entity Type | Asset Sale Treatment | Stock Sale Treatment |
|-------------|---------------------|---------------------|
| **C-Corporation** | Double tax (corp + shareholder) | Single tax (shareholder) |
| **S-Corporation** | Single tax (shareholder) | Single tax (shareholder) |
| **Partnership/LLC** | Single tax (partners) | Single tax (partners) |
| **Sole Proprietorship** | Single tax (owner) | N/A (no stock) |

## Asset Sale Tax Treatment

### For Sellers

**C-Corporation Asset Sale:**
1. Corporation recognizes gain/loss on each asset
2. Character depends on asset type (ordinary vs. capital)
3. Corporation pays tax at 21%
4. Liquidating distribution to shareholders
5. Shareholders pay tax on distribution (capital gain)

**Result: Double taxation**

**S-Corporation/Partnership Asset Sale:**
1. Entity recognizes gain/loss (flows to owners)
2. Character passes through
3. Single level of tax at owner rates
4. Ordinary income recapture still applies

### Asset Allocation (Section 1060)

**Required Allocation Classes (Residual Method):**

| Class | Assets | Character |
|-------|--------|-----------|
| I | Cash and equivalents | None |
| II | Actively traded securities | Capital |
| III | Accounts receivable, inventory | Ordinary |
| IV | Tangible personal property | Mixed |
| V | Real property | 1231/Capital |
| VI | Section 197 intangibles (except goodwill) | Capital |
| VII | Goodwill and going concern | Capital |

**Allocation impacts character of gain/loss**

### Common Ordinary Income Items

| Asset | Recapture Type | Rate |
|-------|----------------|------|
| Inventory | Full ordinary | Up to 37% |
| Accounts receivable | Ordinary | Up to 37% |
| Depreciated equipment | Section 1245 | Up to 37% |
| Depreciated building | Section 1250 | 25% (unrecaptured) |
| Covenant not to compete | Ordinary | Up to 37% |
| Consulting agreements | Ordinary | Up to 37% |

## Stock Sale Tax Treatment

### For Sellers

**Individual Selling Stock:**
- Capital gain (usually long-term)
- Maximum federal rate: 20% + 3.8% NIIT = 23.8%
- Simple calculation: Proceeds - Basis = Gain

**C-Corporation Shareholder:**
- No corporate-level tax
- All gain at shareholder level
- May qualify for QSBS exclusion (Section 1202)

### For Buyers

**Stock Purchase Challenges:**
- No basis step-up in assets
- Continue seller's depreciation schedules
- Inherit all liabilities (known and unknown)
- Inherit tax attributes (NOLs, credits)
- Due diligence critical

## Section 338 Elections

### Section 338(h)(10) Election

**Purpose:** Treat stock sale as asset sale for tax purposes

**Requirements:**
- Target must be S-Corp or member of consolidated group
- Buyer must be corporation
- Joint election by buyer and seller
- Filed within specific timeframe

**Effect:**
- Legal form: Stock sale
- Tax form: Asset sale
- Buyer gets stepped-up basis
- Seller recognizes gain as if assets sold

### When to Use 338(h)(10)

| Factor | Favors 338(h)(10) | Favors Straight Stock |
|--------|-------------------|----------------------|
| Buyer wants step-up | ✓ | |
| Target is S-Corp | ✓ | |
| Low ordinary income assets | ✓ | |
| Large intangible value | ✓ | |
| Buyer is corporation | ✓ | |
| High ordinary recapture | | ✓ |
| Significant built-in gains tax | | ✓ |
| Contract/license non-assignable | ✓ | |

### Section 336(e) Election

**Broader Application:**
- Allows deemed asset sale treatment
- Works for stock sales to any buyer (not just corporations)
- Can apply to qualified stock dispositions
- More flexible than 338(h)(10)

**Requirements:**
- Dispose of 80%+ of target stock
- Within 12-month period
- Joint election

## Tax Calculations

### C-Corporation Asset Sale (Double Tax)

**Sale Price:** $10,000,000

**Asset Allocation:**
| Class | Asset | Value | Basis | Gain |
|-------|-------|-------|-------|------|
| III | Inventory | $500,000 | $300,000 | $200,000 |
| IV | Equipment | $1,500,000 | $500,000 | $1,000,000 |
| V | Building | $3,000,000 | $1,000,000 | $2,000,000 |
| VII | Goodwill | $5,000,000 | $0 | $5,000,000 |
| | **Total** | **$10,000,000** | **$1,800,000** | **$8,200,000** |

**Corporate Tax:**
| Gain Type | Amount | Rate | Tax |
|-----------|--------|------|-----|
| Ordinary (inventory, equipment) | $1,200,000 | 21% | $252,000 |
| Capital (building, goodwill) | $7,000,000 | 21% | $1,470,000 |
| **Corporate Tax** | | | **$1,722,000** |

**Shareholder Tax (Liquidation):**
| Item | Amount |
|------|--------|
| Liquidating distribution | $8,278,000 |
| Shareholder basis | $500,000 |
| Gain | $7,778,000 |
| Tax (23.8%) | $1,851,164 |

**Total Tax: $3,573,164** (35.7% effective rate)

### Stock Sale (Same Transaction)

**Shareholder Tax Only:**
| Item | Amount |
|------|--------|
| Sale proceeds | $10,000,000 |
| Shareholder basis | $500,000 |
| Capital gain | $9,500,000 |
| Tax (23.8%) | **$2,261,000** |

**Tax Savings from Stock Sale: $1,312,164**

### Section 338(h)(10) Example (S-Corp)

**S-Corp Sale - $10,000,000:**

**Without 338(h)(10) (Stock Sale):**
| Item | Amount | Tax (23.8%) |
|------|--------|-------------|
| Gain | $9,500,000 | $2,261,000 |

**With 338(h)(10) (Deemed Asset Sale):**
| Gain Type | Amount | Rate | Tax |
|-----------|--------|------|-----|
| Ordinary | $1,200,000 | 37% | $444,000 |
| Capital | $7,000,000 | 23.8% | $1,666,000 |
| Section 1250 | $500,000 | 25% | $125,000 |
| **Total** | **$8,700,000** | | **$2,235,000** |

**Result:** Similar tax to seller, but buyer gets stepped-up basis worth $1M+ in future depreciation!

## Purchase Price Allocation Strategy

### Buyer Preferences

| Asset Class | Buyer Priority | Why |
|-------------|----------------|-----|
| Section 179 property | High | Immediate deduction |
| 5-year property | High | Fast depreciation |
| Buildings | Moderate | Depreciation + potential sale |
| Goodwill (15-year) | Lower | Slowest amortization |
| Covenant not to compete | Depends | 15-year, but certain deduction |

### Seller Preferences

| Asset Class | Seller Priority | Why |
|-------------|-----------------|-----|
| Goodwill | High | Capital gain |
| Building | Moderate | Capital/1250 gain |
| Equipment | Lower | Ordinary recapture |
| Inventory | Lowest | All ordinary |
| Covenant not to compete | Lowest | All ordinary |

### Negotiating Allocation

**Conflicting Interests:**
- Buyer wants more to depreciable assets
- Seller wants more to capital gain assets
- Total must equal purchase price

**Resolution Methods:**
- Independent appraisals
- Negotiate allocation in purchase agreement
- Binding allocation (IRS challenges rare if reasonable)

## Special Considerations

### Built-In Gains Tax (S-Corporations)

**If converted from C-Corp within 5 years:**
- Asset sale triggers BIG tax (21%)
- On net recognized built-in gain
- Plus shareholder-level tax
- Stock sale may avoid BIG tax

### QSBS (Section 1202)

**Stock Sale Advantage:**
- Up to 100% gain exclusion
- Must be C-Corp stock
- 5-year holding period
- Qualified small business
- Asset sale destroys QSBS benefit

### Installment Sales

**Asset Sale:**
- Can use installment method
- Defer gain over payment period
- Ordinary income recognized first

**Stock Sale:**
- Installment method available
- May be simpler (one asset)
- Watch related party rules

## Case Study

### Scenario

TechCo (S-Corporation):
- Founded 2018, always S-Corp
- Selling for $15,000,000
- Shareholder basis: $1,000,000
- Asset basis: $2,000,000

**Asset Values:**
| Asset | FMV | Basis |
|-------|-----|-------|
| Equipment | $1,000,000 | $200,000 |
| IP/Software | $4,000,000 | $500,000 |
| Customer contracts | $2,000,000 | $0 |
| Goodwill | $8,000,000 | $0 |

**Buyer: Private Equity (Corporation)**

### Option 1: Stock Sale (No 338)

**Seller Tax:**
| Item | Amount |
|------|--------|
| Sale price | $15,000,000 |
| Basis | $1,000,000 |
| Gain | $14,000,000 |
| Tax (23.8%) | **$3,332,000** |

**After-Tax Proceeds:** $11,668,000

**Buyer:** No step-up, continues old depreciation

### Option 2: 338(h)(10) Election

**Seller Tax (Deemed Asset Sale):**
| Asset | Gain | Character | Rate | Tax |
|-------|------|-----------|------|-----|
| Equipment | $800,000 | Ordinary | 37% | $296,000 |
| IP/Software | $3,500,000 | Capital | 23.8% | $833,000 |
| Customer contracts | $2,000,000 | Capital | 23.8% | $476,000 |
| Goodwill | $8,000,000 | Capital | 23.8% | $1,904,000 |
| **Total** | **$14,300,000** | | | **$3,509,000** |

**After-Tax Proceeds:** $11,491,000

**Buyer Benefit:**
- Step-up in all assets
- Depreciation/amortization: $15M over 5-15 years
- NPV of step-up: ~$2,500,000

### Negotiating the Difference

| Scenario | Seller After-Tax | Buyer Benefit |
|----------|------------------|---------------|
| Stock sale | $11,668,000 | $0 |
| 338(h)(10) | $11,491,000 | $2,500,000 |
| **Difference** | **($177,000)** | **$2,500,000** |

**Solution:** Buyer pays $15,250,000 with 338(h)(10) election
- Seller after-tax: ~$11,650,000 (similar)
- Buyer benefit: ~$2,300,000 (still significant)
- **Win-win through negotiation**

## Common Mistakes

| Mistake | Consequence | Prevention |
|---------|-------------|------------|
| Not modeling both structures | Leave money on table | Run both scenarios |
| Ignoring allocation | Suboptimal tax result | Negotiate allocation |
| Missing 338 election deadline | Lose step-up opportunity | File timely |
| Forgetting BIG tax | Unexpected tax | Calculate pre-sale |
| Not considering QSBS | Miss exclusion | Evaluate before structuring |
| Inconsistent buyer/seller allocation | IRS adjustment | Form 8594 consistency |

## Key Tax Code References

- **IRC Section 338**: Stock purchase treated as asset acquisition
- **IRC Section 336(e)**: Deemed asset sale election
- **IRC Section 1060**: Purchase price allocation
- **IRC Section 197**: Amortization of intangibles
- **IRC Section 1245**: Depreciation recapture (personal property)
- **IRC Section 1250**: Depreciation recapture (real property)
- **IRC Section 1374**: Built-in gains tax
- **IRC Section 1202**: QSBS exclusion
- **Form 8594**: Asset acquisition statement
- **Form 8023**: Section 338 election

## Related Strategies

- [Exit Planning](exit-planning.md)
- [QSBS](qsbs.md)
- [Installment Sales](installment-sales.md)
- [Entity Structuring](entity-structuring.md)
- [S-Corp Reasonable Compensation](s-corp-reasonable-compensation.md)

---

*Last Updated: November 2025 (Post-OBBBA)*
*Model BOTH Structures Before Finalizing Any Business Sale*
