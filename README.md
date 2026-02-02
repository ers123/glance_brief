# AI State Reports 2025-2026: 10 Key Findings Extraction

> **Timeframe**: November 2025 - January 2026
> **Reports**: 72 verified reports from MBB, Big 4, Big Tech, Investment Banks, and Think Tanks

---

## 📋 Project Overview

This project extracts **10 Key Findings** from major AI/Tech reports published between November 2025 and January 2026. Each report is transformed into a sharp, investor-grade summary format.

### Output Format Example

```
**Goldman Sachs - Why AI Companies May Invest More than $500 Billion in 2026: 10 Key Findings (Sharp & Short)**

**1. Wall Street keeps getting it wrong**: Analysts projected $465 billion for 2026 just months ago.
Now it's $527 billion. They've underestimated for two years straight.

**2. $106 billion in one quarter**: Hyperscalers burned through $106 billion in Q3 2025 alone,
up 75% year-over-year...
```

---

## 📁 Repository Structure

```
glance_brief/
├── README.md                          # This file
├── index_exists_only.csv              # 72 verified reports with URLs
├── CODEX_PROMPT_10_KEY_FINDINGS.md    # Prompt template + examples
└── outputs/
    ├── MBB/                           # McKinsey, BCG, Bain
    ├── Big4/                          # Deloitte, EY, KPMG, PwC
    ├── IT_Consulting/                 # Accenture, Capgemini, IBM, TCS, etc.
    ├── Big_Tech/                      # Google, Microsoft, OpenAI, Anthropic, NVIDIA, etc.
    ├── IB/                            # Goldman Sachs, Morgan Stanley, JPMorgan, etc.
    ├── VC/                            # ARK Invest, Gartner
    ├── Think_Tank/                    # OECD, UN/ITU, MIT Tech Review
    └── Government/                    # Japan, Korea, Singapore, India
```

---

## 🚀 How to Use with Codex Web (OpenAI)

### Step 1: Initial Setup
```
Read CODEX_PROMPT_10_KEY_FINDINGS.md to understand the output format.
Read index_exists_only.csv to see the list of reports to process.
```

### Step 2: Batch Processing Prompt
```
Process reports #1-10 from index_exists_only.csv:

For each report:
1. Visit the URL in "Corrected_URL" column
2. Extract 10 Key Findings following CODEX_PROMPT_10_KEY_FINDINGS.md format
3. Save as markdown in outputs/{Category}/ folder

Filename convention: {#}_{Publisher}_{ShortTitle}.md
Example: 01_McKinsey_StateOfAI2025.md

Start with MBB category.
```

### Step 3: Continue in Batches
```
Continue with reports #11-20...
Continue with reports #21-30...
(repeat until all 72 reports are processed)
```

---

## 📊 Report Categories

| Category | Count | Publishers |
|----------|-------|------------|
| MBB | 17 | McKinsey, BCG, Bain |
| Big4 | 13 | Deloitte, EY, KPMG, PwC |
| IT Consulting | 8 | Accenture, Capgemini, IBM, TCS, Cognizant |
| Big Tech | 18 | Google, Microsoft, AWS, NVIDIA, Anthropic, OpenAI, Apple, Baidu |
| IB | 5 | Goldman Sachs, Morgan Stanley, JPMorgan, BofA, Citi |
| VC/Analyst | 2 | ARK Invest, Gartner |
| Think Tank | 4 | OECD, UN/ITU, MIT Tech Review |
| Government | 5 | Japan, Korea, Singapore, India |

**Total: 72 reports**

---

## 📝 CSV Column Reference

| Column | Description |
|--------|-------------|
| # | Report number (1-103, non-sequential for EXISTS only) |
| Date | Publication date (YYYY-MM format) |
| Report Name | Full report title |
| Publisher | Organization name |
| Tier | Priority tier (1 or 2) |
| Category | MBB, Big4, Big_Tech, IB, etc. |
| Corrected_URL | Verified working URL |
| Format | Article, PDF, Landing, etc. |

---

## ✅ Quality Checklist

Before submitting each output, verify:
- [ ] Exactly 10 findings (no more, no less)
- [ ] Each finding has a punchy 2-5 word headline
- [ ] Each finding is 2-4 sentences max
- [ ] Lead with striking statistics/claims
- [ ] End with memorable closing lines
- [ ] No corporate jargon
- [ ] All claims traceable to source

---

## 📅 Project Timeline

- **Data Collection**: November 2025 - January 2026 reports
- **URL Verification**: Completed February 2, 2026
- **10 Key Findings Extraction**: In Progress

---

## 🔗 Related Resources

- [Goldman Sachs Example Output](https://www.goldmansachs.com/insights/articles/why-ai-companies-may-invest-more-than-500-billion-in-2026)
- Original prompt inspired by investor-grade research formats

---

*Last updated: February 2, 2026*
