# Contributing to CJCPAs Ultimate Tax Strategy Database

Thank you for your interest in contributing to this tax strategy database! This guide explains how to submit new strategies, update existing content, and ensure your contributions meet our quality standards.

## Table of Contents

- [Before You Contribute](#before-you-contribute)
- [Types of Contributions](#types-of-contributions)
- [Strategy Document Format](#strategy-document-format)
- [Style Guidelines](#style-guidelines)
- [Submission Process](#submission-process)
- [Review Criteria](#review-criteria)
- [Legal and Compliance Notes](#legal-and-compliance-notes)

---

## Before You Contribute

### Who Should Contribute

This database is maintained by and for tax professionals. Contributors should have:

- Professional tax knowledge (CPA, EA, tax attorney, or equivalent experience)
- Familiarity with current tax law and IRS guidance
- Understanding of the practical application of tax strategies

### Prerequisites

1. **Read existing strategies** - Review 2-3 existing strategy documents to understand our format and depth
2. **Verify accuracy** - All information must be based on current tax law (IRC, Treasury Regulations, IRS guidance)
3. **Check for duplicates** - Ensure your strategy isn't already covered in the database

---

## Types of Contributions

### 1. New Strategy Documents

Adding a completely new tax strategy not currently in the database.

**Requirements:**
- Strategy must be legal and based on established tax law
- Must have practical application for clients
- Should include sufficient detail for implementation

### 2. Updates to Existing Strategies

Corrections, clarifications, or updates due to law changes.

**Common updates include:**
- New legislation (e.g., OBBBA provisions)
- Updated thresholds and limits (inflation adjustments)
- New IRS guidance or court cases
- Correcting errors or outdated information

### 3. Case Studies and Examples

Adding practical examples to existing strategies.

**Requirements:**
- Realistic scenarios with specific numbers
- Clear before/after comparisons showing tax impact
- Proper disclaimers about hypothetical nature

### 4. Bug Fixes and Corrections

Fixing typos, broken links, calculation errors, or formatting issues.

---

## Strategy Document Format

All strategy documents must follow this standardized format. Copy the template below for new strategies.

### Required Sections

| Section | Purpose |
|---------|---------|
| **Title (H1)** | Clear, descriptive strategy name |
| **Overview** | 2-3 paragraph summary of the strategy |
| **Key Benefits** | Bullet list of primary advantages |
| **Requirements** | Eligibility criteria and prerequisites |
| **Client Fit Criteria** | Ideal, good, and challenging candidate profiles |
| **Implementation Steps** | Detailed, numbered steps to execute |
| **Risks & Considerations** | Potential pitfalls and audit concerns |
| **Case Study** | Practical example with numbers |
| **Key Tax Code References** | IRC sections, regulations, and guidance |
| **Related Strategies** | Links to complementary strategies |

### Optional Sections

- Effective Dates & Key Law Changes (for strategies affected by recent legislation)
- Calculation tables and formulas
- State-specific considerations
- Common mistakes to avoid

### Template

```markdown
# [Strategy Name]

## Overview

[2-3 paragraphs explaining what the strategy is, how it works, and why it matters. Include any recent law changes that affect the strategy.]

## Effective Dates & Key Law Changes

| Provision | Previous Law | Current Law |
|-----------|--------------|-------------|
| [Item] | [Old rule] | [New rule] |

## Key Benefits

- **[Benefit 1]:** [Description]
- **[Benefit 2]:** [Description]
- **[Benefit 3]:** [Description]

## Requirements

### [Requirement Category 1]
- [Specific requirement]
- [Specific requirement]

### [Requirement Category 2]
- [Specific requirement]
- [Specific requirement]

## Client Fit Criteria

### Ideal Candidates
- [Profile description]
- [Profile description]

### Good Candidates
- [Profile description]
- [Profile description]

### Challenging Scenarios
- [Profile description]
- [Profile description]

## Implementation Steps

### Step 1: [Step Name]

1. **[Action Item]**
   - [Detail]
   - [Detail]

2. **[Action Item]**
   - [Detail]
   - [Detail]

### Step 2: [Step Name]

[Continue pattern...]

## Risks & Considerations

### [Risk Category 1]
- [Specific risk]
- [Mitigation approach]

### [Risk Category 2]
- [Specific risk]
- [Mitigation approach]

## Case Study

### Scenario
[Describe client situation with specific facts and numbers]

### Without Strategy
- [Result without planning]
- **Tax impact: $X**

### With Strategy
- [Result with planning]
- **Tax impact: $Y**

**Annual Tax Savings: $[X-Y]**

## Key Tax Code References

- **IRC Section [XXX]**: [Description]
- **Treas. Reg. [X.XXX-X]**: [Description]
- **[IRS Notice/Rev. Proc.]**: [Description]

## Related Strategies

- [Strategy Name](strategy-file.md)
- [Strategy Name](strategy-file.md)

---

*Last Updated: [Month Year]*
```

---

## Style Guidelines

### Writing Style

- **Be precise** - Use specific numbers, thresholds, and dates
- **Be practical** - Focus on implementation, not just theory
- **Be current** - Reference the most recent law (OBBBA 2025 where applicable)
- **Be professional** - Write for an audience of tax professionals

### Formatting Rules

1. **Headings**: Use H2 (`##`) for main sections, H3 (`###`) for subsections
2. **Lists**: Use bullet points for items, numbered lists for sequential steps
3. **Tables**: Use markdown tables for thresholds, comparisons, and calculations
4. **Bold**: Use for key terms, amounts, and emphasis
5. **Links**: Use relative links for internal references (`[Strategy](strategy.md)`)

### Numbers and Amounts

- Use **$X,XXX** format with commas for dollar amounts
- Express percentages as **X%** (e.g., 23%, not .23 or 23 percent)
- Include tax year when thresholds are year-specific
- Round to reasonable precision (don't show $123,456.78 when $123,500 suffices for illustration)

### Tax Law References

Always cite primary sources:

| Source Type | Format Example |
|-------------|----------------|
| IRC Section | IRC Section 199A |
| Treasury Regulation | Treas. Reg. 1.199A-1 |
| Revenue Ruling | Rev. Rul. 2023-XX |
| Revenue Procedure | Rev. Proc. 2023-XX |
| IRS Notice | Notice 2023-XX |
| Court Case | *Smith v. Commissioner*, T.C. Memo 2023-XX |

---

## Submission Process

### Step 1: Fork and Clone

```bash
# Fork the repository on GitHub, then:
git clone https://github.com/YOUR-USERNAME/CJCPAs-Ultimate-Tax-Strategy-Database.git
cd CJCPAs-Ultimate-Tax-Strategy-Database
```

### Step 2: Create a Branch

```bash
git checkout -b feature/strategy-name
# or for updates:
git checkout -b update/strategy-name-description
```

### Step 3: Make Your Changes

- Add new strategies to the `strategies/` folder
- Use lowercase with hyphens for filenames (e.g., `new-strategy-name.md`)
- Update `README.md` table of contents if adding a new strategy

### Step 4: Test Your Changes

- Verify all links work
- Check markdown renders correctly
- Confirm calculations are accurate
- Proofread for typos

### Step 5: Commit and Push

```bash
git add .
git commit -m "Add [strategy name] strategy"
# or "Update [strategy] with [description of changes]"
git push origin feature/strategy-name
```

### Step 6: Open a Pull Request

- Provide a clear title describing the contribution
- Include a summary of what was added/changed
- Reference any relevant tax law changes
- Note if the change affects other strategies

---

## Review Criteria

All contributions are reviewed against these criteria:

### Accuracy (Required)

- [ ] Tax law citations are correct and current
- [ ] Calculations and examples are mathematically accurate
- [ ] Thresholds and limits reflect current law
- [ ] No outdated or superseded guidance

### Completeness (Required)

- [ ] All required sections are present
- [ ] Implementation steps are actionable
- [ ] Risks are adequately disclosed
- [ ] Client fit criteria help practitioners identify suitable clients

### Clarity (Required)

- [ ] Writing is clear and professional
- [ ] Complex concepts are explained
- [ ] Examples illustrate key points
- [ ] Formatting follows guidelines

### Practicality (Preferred)

- [ ] Strategy has real-world application
- [ ] Case study is realistic
- [ ] Implementation is feasible
- [ ] Benefits justify complexity

---

## Legal and Compliance Notes

### Disclaimer

This database is for educational and informational purposes. Contributors should understand:

1. **No tax advice** - Content should inform, not advise specific taxpayers
2. **Professional judgment required** - Strategies require professional analysis
3. **Facts and circumstances** - Results depend on individual situations
4. **State variations** - Strategies may differ by state jurisdiction

### Prohibited Content

Do not submit:

- Strategies based on tax fraud or evasion
- Schemes lacking economic substance
- Listed transactions or substantially similar arrangements
- Content promoting abusive tax shelters
- Strategies relying on non-disclosure to succeed

### Attribution

- Cite sources for data, statistics, or quoted material
- Do not copy content from copyrighted sources without permission
- Original analysis and explanation is expected

---

## Questions?

If you have questions about contributing:

1. **Check existing strategies** for format examples
2. **Review the README** for database structure
3. **Open an issue** for questions about specific strategies or contribution process

---

## Change Log Protocol

When making updates, add an entry to the Change Log section in README.md:

```markdown
| Date | Change | Files Affected |
|------|--------|----------------|
| [YYYY-MM-DD] | [Brief description] | [List of files] |
```

---

*Thank you for helping keep this database accurate and comprehensive!*
