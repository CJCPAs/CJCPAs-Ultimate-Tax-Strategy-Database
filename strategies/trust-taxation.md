# Trust Taxation Deep Dive

## Overview

Trusts are separate taxpaying entities with their own set of tax rules, rates, and planning opportunities. The most striking feature of trust taxation is the highly compressed tax brackets—trusts reach the top 37% rate at just $14,450 of taxable income (2024), compared to $609,350 for single individuals. This compression creates both challenges and planning opportunities that every advisor should understand.

## Effective Dates & Key Law Changes (Post-OBBBA)

| Provision | 2024 | 2025+ (OBBBA) |
|-----------|------|---------------|
| Top Trust Bracket | 37% at $14,450 | **37% (permanent)** ~$15,200 |
| 20% Capital Gains Bracket | $14,450 | ~$15,200 (indexed) |
| 3.8% NIIT Threshold | $14,450 | ~$15,200 (indexed) |
| Standard Deduction | None | None |
| Personal Exemption | $100/$300 | $100/$300 |
| Section 199A | 20% | **23% (permanent)** |
| Charitable Deduction | Available | Available |

**OBBBA Update:** TCJA rates were made permanent. The 37% top bracket remains, and Section 199A is now permanent at 23%. Trust income planning remains critical due to compressed brackets.

## Trust Tax Basics

### Compressed Tax Brackets (2024)

**Trust and Estate Tax Brackets:**

| Taxable Income | Tax Rate |
|----------------|----------|
| $0 - $3,100 | 10% |
| $3,100 - $11,150 | 24% |
| $11,150 - $14,450 | 35% |
| Over $14,450 | 37% |

**Comparison to Individual (Single):**

| Income Level | Trust Rate | Individual Rate |
|--------------|------------|-----------------|
| $10,000 | 24% | 10% |
| $50,000 | 37% | 22% |
| $100,000 | 37% | 24% |
| $500,000 | 37% | 35% |

**Key Point:** Trust reaches 37% rate 42x faster than individuals!

### Types of Trusts for Tax Purposes

| Trust Type | Taxation | When Used |
|------------|----------|-----------|
| **Grantor Trust** | Income taxed to grantor | GRATs, IDGTs, revocable trusts |
| **Simple Trust** | Must distribute all income; taxed to beneficiaries | Income trusts |
| **Complex Trust** | May accumulate income; may have charitable beneficiaries | Discretionary trusts |
| **Grantor Retained Trusts** | Grantor taxed (grantor trust) | GRATs, QPRTs |

### Trust Accounting Income vs. Taxable Income

**Key Distinction:**

| Concept | Definition | Use |
|---------|------------|-----|
| **Trust Accounting Income (TAI)** | Income under trust document and state law | Determines required distributions |
| **Distributable Net Income (DNI)** | Modified taxable income | Limits deduction for distributions |
| **Taxable Income** | Income after deductions | Actual tax calculation |

## Grantor Trusts

### Definition

A grantor trust is one where the grantor retains certain powers or interests that cause the trust income to be taxed to the grantor personally, not the trust.

### Grantor Trust Triggers (Section 671-679)

| Trigger | Code Section |
|---------|--------------|
| Power to revoke | 676 |
| Reversionary interest >5% | 673 |
| Power over beneficial enjoyment | 674 |
| Administrative powers (grantor benefit) | 675 |
| Power to substitute assets | 675(4)(C) |
| Income for grantor/spouse benefit | 677 |
| Power to add beneficiaries | 674(a) |

### Tax Treatment

**Grantor Trust:**
- All income, deductions, credits flow to grantor
- Trust files Form 1041 (informational)
- Grantor reports on personal return
- No compressed brackets (uses grantor's brackets)

### Planning Implications

**Advantages:**
- Avoid compressed trust brackets
- Grantor paying tax = additional tax-free gift to beneficiaries
- No gain on sales between grantor and trust

**When Intentional:**
- IDGTs (Intentionally Defective Grantor Trusts)
- GRATs
- Installment sales to trusts

## Simple Trusts

### Requirements

1. Must distribute all income currently
2. Cannot distribute principal
3. No charitable beneficiaries
4. (For that year—same trust can be complex in other years)

### Taxation

**Income Distribution Deduction:**
- Trust gets deduction for distributions
- Beneficiaries report income received
- Character of income flows through (DNI)

### Calculation Example

| Item | Amount |
|------|--------|
| Interest income | $50,000 |
| Dividends | $20,000 |
| Capital gains (allocated to principal) | $30,000 |
| Trust Accounting Income | $70,000 |
| Required distribution | $70,000 |
| Distribution deduction | $70,000 |
| Trust taxable income | $30,000 (capital gains only) |

## Complex Trusts

### Characteristics

- May accumulate income
- May distribute principal
- May have charitable beneficiaries
- Most discretionary trusts are complex

### Distributable Net Income (DNI)

**DNI Calculation:**

```
Taxable Income
+ Tax-exempt interest (net of allocable expenses)
+ Personal exemption
- Capital gains (allocated to principal)
- Extraordinary dividends (allocated to principal)
= DNI
```

**DNI Limits:**
1. Trust's deduction for distributions cannot exceed DNI
2. Beneficiary's inclusion cannot exceed DNI

### Distribution Deduction

**For Complex Trust:**
```
Distribution Deduction = Lesser of:
(1) Actual distributions, or
(2) DNI
```

### Tier System for Distributions

| Tier | Priority | Consists Of |
|------|----------|-------------|
| **Tier 1** | First | Required income distributions |
| **Tier 2** | Second | All other distributions |

**DNI allocated first to Tier 1, then to Tier 2**

## The 65-Day Rule (Section 663(b))

### Overview

Trustee can elect to treat distributions made within first 65 days of year as made on last day of prior year.

### Application

**Example:**
- Trust year-end: December 31, 2025
- Distribution made: February 15, 2026
- With 663(b) election: Treated as made December 31, 2025
- Result: Reduces 2025 trust income

### Requirements

- Must elect on timely filed return (including extensions)
- Distribution must be made within 65 days of year-end
- Cannot exceed greater of TAI or DNI

### Strategic Use

| Situation | 65-Day Rule Benefit |
|-----------|---------------------|
| Unexpected year-end income | Distribute to lower-bracket beneficiaries |
| Tax planning opportunity | Shift income to better year |
| Forgot to distribute | Cure missed distribution |

## Capital Gains in Trusts

### Default Treatment

**General Rule:** Capital gains allocated to principal (corpus), not DNI

**Result:** Trust pays tax on capital gains at compressed rates (up to 23.8%)

### Including Capital Gains in DNI

**Can include capital gains in DNI if:**
1. Trust document allocates to income
2. Consistent practice of treating as income
3. Actually distributed as part of distribution
4. State law permits

**Why Include?**
- Shift capital gains to lower-bracket beneficiaries
- Reduce compressed bracket impact
- Better overall tax result

## Trust Tax Planning Strategies

### Strategy 1: Distribute Income (The Primary Strategy)

**Avoid Compressed Brackets:**
| Distribution Level | Trust Tax | Beneficiary Tax* | Total |
|--------------------|-----------|------------------|-------|
| $0 (accumulate) | $5,355 on $14,450 | $0 | $5,355 |
| $14,450 (distribute) | $0 | $1,445 | $1,445 |
| **Savings** | | | **$3,910** |

*Assuming beneficiary in 10% bracket

### Strategy 2: Use 65-Day Rule

**Year-End Planning:**
1. Review trust income after year-end
2. Decide on distributions by March 6
3. Make election on Form 1041
4. Reduce prior year trust tax

### Strategy 3: Elect Grantor Trust Status

**For new trusts:**
- Include grantor trust power
- Tax at grantor's (usually lower) rates
- Grantor pays tax = gift to beneficiaries

### Strategy 4: Invest for Tax Efficiency

**In Accumulated Trusts:**
| Investment | Trust Treatment |
|------------|-----------------|
| Growth stocks | Deferred gains |
| Municipal bonds | Tax-exempt |
| Qualified dividends | 20% max rate |
| Index funds | Low turnover |
| REITs | Ordinary income (avoid) |

### Strategy 5: Charitable Deductions

**Complex trusts can deduct:**
- Amounts paid to charity
- From gross income
- No percentage limitation (unlike individuals)

### Strategy 6: QSST and ESBT for S-Corp Stock

**Qualified Subchapter S Trust (QSST):**
- One income beneficiary
- All income distributed
- Taxed to beneficiary

**Electing Small Business Trust (ESBT):**
- Multiple beneficiaries allowed
- S-Corp income taxed at highest rate
- More flexible but worse tax treatment

## Trust Tax Calculations

### Complete Trust Tax Example

**The Williams Family Trust (Complex Trust):**

**Income:**
| Item | Amount |
|------|--------|
| Interest | $30,000 |
| Dividends (qualified) | $20,000 |
| Capital gains | $50,000 |
| Rental income | $25,000 |
| **Total** | **$125,000** |

**Expenses:**
| Item | Amount |
|------|--------|
| Trustee fees | $5,000 |
| Tax preparation | $2,000 |
| Investment management | $3,000 |
| **Total** | **$10,000** |

**Distributions:**
| Beneficiary | Amount |
|-------------|--------|
| Child 1 | $30,000 |
| Child 2 | $30,000 |
| **Total** | **$60,000** |

**Tax Calculation:**

**Step 1: Calculate DNI**
| Item | Amount |
|------|--------|
| Total income | $125,000 |
| Less: Capital gains | ($50,000) |
| Less: Allocable expenses | ($8,000) |
| **DNI** | **$67,000** |

**Step 2: Distribution Deduction**
| Item | Amount |
|------|--------|
| Actual distributions | $60,000 |
| DNI | $67,000 |
| **Distribution deduction** | **$60,000** |

**Step 3: Trust Taxable Income**
| Item | Amount |
|------|--------|
| Total income | $125,000 |
| Less: Distribution deduction | ($60,000) |
| Less: Expenses | ($10,000) |
| Less: Exemption | ($100) |
| **Taxable income** | **$54,900** |

**Step 4: Trust Tax**
| Component | Amount | Rate | Tax |
|-----------|--------|------|-----|
| Ordinary ($54,900 - $50,000 CG) | $4,900 | 37% | $1,813* |
| Capital gains | $50,000 | 20% | $10,000 |
| NIIT ($54,900) | $54,900 | 3.8% | $2,086 |
| **Total trust tax** | | | **$13,899** |

*Simplified; actual brackets apply

**Beneficiary Reporting:**
| Child | Share of DNI | Tax (est. 24%) |
|-------|--------------|----------------|
| Child 1 | $30,000 | $7,200 |
| Child 2 | $30,000 | $7,200 |
| **Total** | **$60,000** | **$14,400** |

**Total Family Tax: $28,299**

### What If Trust Accumulated All?

| Item | Amount |
|------|--------|
| Taxable income | $114,900 |
| Tax on ordinary ($64,900) | ~$23,000 |
| Tax on capital gains | $10,000 |
| NIIT | $4,366 |
| **Total trust tax** | **~$37,366** |

**Savings from distributing: ~$9,000**

## Reporting Requirements

### Form 1041

**Due Date:** April 15 (calendar year) or 15th day of 4th month after year-end

**Key Schedules:**
| Schedule | Purpose |
|----------|---------|
| Schedule B | Income distribution deduction |
| Schedule D | Capital gains and losses |
| Schedule E | Rental income |
| Schedule G | Tax computation |
| Schedule K-1 | Beneficiary allocations |

### Schedule K-1 (Form 1041)

**Reports to beneficiaries:**
- Share of income by type
- Deductions passed through
- Credits allocated
- Alternative minimum tax items

### State Filings

**Trust residency varies by state:**
| Factor | States Using |
|--------|--------------|
| Grantor residence | CA, NY, others |
| Trustee residence | Some states |
| Beneficiary residence | Some states |
| Administration location | Some states |
| Trust formation | DE, NV, SD |

**May owe tax in multiple states!**

## Common Mistakes

| Mistake | Consequence | Prevention |
|---------|-------------|------------|
| Accumulating income unnecessarily | Compressed bracket tax | Distribute to beneficiaries |
| Missing 65-day election | Higher prior year tax | Mark calendar |
| Wrong DNI calculation | Incorrect distributions | Follow formula carefully |
| Ignoring NIIT | Unexpected 3.8% tax | Include in projections |
| Not allocating expenses | Overstated DNI | Properly allocate |
| Forgetting K-1s | Beneficiary penalties | File timely |

## Key Tax Code References

- **IRC Section 641**: Imposition of trust tax
- **IRC Section 643**: DNI definition
- **IRC Section 651-652**: Simple trusts
- **IRC Section 661-663**: Complex trusts
- **IRC Section 671-679**: Grantor trust rules
- **IRC Section 1(e)**: Trust tax rates
- **IRC Section 1411**: Net Investment Income Tax
- **IRC Section 199A**: QBI deduction for trusts
- **Form 1041**: U.S. Income Tax Return for Estates and Trusts
- **Schedule K-1 (1041)**: Beneficiary's Share

## Related Strategies

- [Dynasty Trusts](dynasty-trusts.md)
- [GRATs](grats.md)
- [IDGTs](idgts.md)
- [SLATs](slats.md)
- [Charitable Lead Trusts](charitable-lead-trusts.md)

---

*Last Updated: November 2025 (Post-OBBBA)*
*Trusts Hit 37% at ~$15,200—Distribute Income When Possible!*
