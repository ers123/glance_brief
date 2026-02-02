# Anthropic Economic Index Report: Economic Primitives

**URL:** https://www.anthropic.com/research/anthropic-economic-index-january-2026-report

**Date:** January 15, 2026

**Category:** Economic Research

## Executive Summary

This fourth Anthropic Economic Index Report introduces economic primitives—foundational characteristics of AI interactions that provide insight into how AI is reshaping the economy. The report analyzes over 1 million Claude.ai conversations and 1P API records to understand patterns of AI usage, adoption, and economic impact across different geographies, tasks, and use cases.

## Key Findings

### What Has Changed Since the Previous Report

**Usage Concentration:**
- The ten most common tasks represent 24% of observed usage on Claude.ai, up from 23% in the last report
- Usage remains highly concentrated across certain tasks, most of them related to coding
- While substantial concentration remains, Claude usage has become noticeably more diverse

**Collaboration Modes:**
- Augmentation is once again more common than automation on Claude.ai
- After reaching 39% in September 2025 (automated use exceeded augmented use), directive conversations fell to 32% in November 2025
- The shift reflects new file creation capabilities, persistent memory, and Skills for workflow customization

**US Regional Adoption:**
- Within the US, usage per capita remains largely shaped by workforce composition matching to broad AI applications
- Lower usage states have relatively faster gains in adoption
- Claude usage has become more evenly distributed across US states from August to November 2025

**Global Usage Patterns:**
- Global usage shows persistent regional concentration
- Five countries lead in overall Claude.ai use: US, India, Japan, UK, and South Korea
- Global usage shows little sign of increasing or decreasing regional convergence at the country level

### New Economic Primitives

The report introduces five new economic primitives beyond the collaboration pattern metric:

**1. Task Complexity**
- Captures how long tasks take to complete and their difficulty
- Tasks can vary significantly in complexity and duration
- Claude estimates suggest substantial variation across different work types

**2. Human and AI Skills**
- Measures education levels required for task understanding
- Addresses how automation interacts with skill levels
- Disproportionate substitution for lower-skill tasks has different labor market implications than substitution at other skill levels

**3. Use Case**
- Distinguishes professional, educational, and personal use
- Labor market effects most directly follow from professional use
- Over 1 million Claude.ai conversations analyzed for privacy-preserving classification

**4. AI Autonomy**
- Measures the degree to which users delegate decision-making to Claude
- Ranges on a scale of approximately 1-5
- Documented patterns of where users trust Claude to act independently

**5. Task Success**
- Measures Claude's assessment of whether it completes tasks successfully
- Helps assess model reliability and capability
- Task success correlates with task complexity and varies by use case

### Geographic Variation in Usage

**Work vs. Personal Use:**
- Work and personal use cases are more common in higher-income countries
- Coursework use cases are most common in countries with lower per capita income
- A 1% increase in GDP per capita is associated with a 0.7% increase in Claude usage per capita

**Global Adoption Patterns:**
- GDP per capita and human education level predict adoption globally
- At the country level, higher usage correlates with shorter tasks and less AI autonomy
- Other primitives predict adoption differently at global vs. US state levels
- Near-perfect correlation (r > 0.92) between human and AI education years

### Task and Productivity Insights

**Speedup and Success Tradeoff:**
- More complex tasks yield greater time savings when AI succeeds
- More complex tasks have lower task success rates
- API users consistently see higher speedups than Claude.ai users across task complexity ranges

**Task Horizons in Real-World Usage:**
- Recent research on AI "task horizons" finds that AI success rates decline with task duration
- In API data, success rates decline as task duration increases
- In Claude.ai data, success rates decline far slower as a function of task length
- Fundamental difference: selection bias in Claude.ai where users may avoid tasks they expect to fail

**Effective AI Coverage:**
- Task coverage (measuring whether AI is used for at least some tasks in a job) differs from effective AI coverage
- Effective AI coverage measures the percent of a worker's day that can be performed successfully with AI
- 49% of jobs have seen AI usage across reports
- Many occupations show large differences between task coverage and effective AI coverage

**Job Task Content Changes:**
- Claude tends to cover tasks that require higher levels of education
- Some jobs see average education levels increase (upskilling) when AI-covered tasks are removed
- Other jobs may experience downskilling as their remaining task mix changes
- Patterns illustrate how jobs may evolve as their task content adjusts

### Productivity Impact Estimates

**Aggregate Productivity Implications:**
- Earlier research estimated that widespread adoption of Claude could increase US labor productivity growth by 1.8 percentage points annually over the next decade
- When accounting for model reliability and task success rates, implied productivity growth falls from 1.8 to 1.2 percentage points
- Results depend significantly on the elasticity of substitution across tasks

**Task Substitutability Effects:**
- When tasks are complements (elasticity < 1), implied aggregate labor productivity impact declines sharply
- When elasticity > 1, implied labor productivity impact is more moderate
- API traffic shows more responsiveness to the degree of task substitutability than Claude.ai data
- Productivity effects of automation may ultimately be constrained by task complementarity

## Differences Between Claude.ai and API Usage

**API Users:**
- 74% work-related (vs. 46% for Claude.ai)
- 64% directive/automation mode (vs. 32% for Claude.ai)
- Overwhelmingly focused on systematic automation
- Concentrate on tasks amenable to systematic automation

**Claude.ai Users:**
- More back-and-forth interaction patterns
- Higher rates of task iteration and learning modes
- More diverse occupational distribution
- More exploratory and augmentation-focused usage patterns

## Data Methodology

- Analysis covers 1 million Claude.ai Free, Pro and Max conversations from November 13-29, 2025
- Privacy-preserving analysis methodology (Clio framework)
- 5+ new dimensions of data collection
- External researcher access to anonymized datasets via Hugging Face

## Top Common Tasks

Computer and mathematical tasks dominate usage:
- Modifying software to correct errors continues to dominate
- Second largest share: Educational Instruction and Library Science
- Growing share: Arts, Design, Entertainment, Sports, and Media tasks
- Increasing automation use cases for transcription on API

## Concluding Remarks

This report introduces foundational metrics for understanding AI's economic impact beyond mere adoption rates. Key insights include:

1. **Geographic Heterogeneity:** AI's impact on the economy will be uneven, with different regions showing different adoption patterns and use cases

2. **Skill-Based Effects:** The concentration of AI use on higher-skill tasks suggests differential labor market effects by skill level

3. **Human-AI Alignment:** The near-perfect correlation between human and AI education levels shows that how users prompt reflects how Claude responds

4. **Future Implications:** As AI adoption increases and capabilities improve, we can expect shifts in job task content, skill requirements, and labor market dynamics

5. **Data Transparency:** The report significantly expands the scope and transparency of usage data available to researchers and the public

## Authors

**Lead Authors:**
- Ruth Appel
- Maxim Massenkoff
- Peter McCrory

**Contributors:**
- Miles McCain
- Ryan Heller
- Tyler Neylon
- Alex Tamkin

## Resource Links

- Full PDF Report Available
- Dataset: https://huggingface.co/datasets/Anthropic/EconomicIndex
- Previous Report: Anthropic Economic Index September 2025
