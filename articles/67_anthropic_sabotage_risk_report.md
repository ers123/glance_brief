# Anthropic's Pilot Sabotage Risk Report

**URL:** https://alignment.anthropic.com/2025/sabotage-risk-report/

**Authors:** Samuel R. Bowman, Misha Wagner, Fabien Roger, and Holden Karnofsky

**Date:** October 28, 2025

## Overview

As practice for potential future Responsible Scaling Policy obligations, Anthropic is releasing a report on misalignment risk posed by their deployed models as of Summer 2025. The report concludes that there is very low, but not fully negligible, risk of misaligned autonomous actions that substantially contribute to later catastrophic outcomes.

## Key Takeaways

- **Risk Level Assessment:** Very low, but not completely negligible risk of misaligned autonomous actions that could contribute significantly to later catastrophic outcomes, abbreviated as sabotage risk

- **Threat Models:** Multiple sabotage-related threat models with similar but low levels of absolute risk

- **Claude Opus 4 Confidence:** Moderately confident that Opus 4 does not have consistent, coherent dangerous goals, and that it does not have the capabilities needed to reliably execute complex sabotage strategies while avoiding detection

## Report Purpose

The Responsible Scaling Policy includes future commitments addressing misalignment-related risks that initiate from the model's own behavior. For future models that pass a capability threshold not yet reached, it commits Anthropic to developing an affirmative case that:

1. Identifies the most immediate and relevant risks from models pursuing misaligned goals
2. Explains how these risks have been mitigated to acceptable levels

This pilot exercise aims to:
- Give early visibility into issues that might arise in preparing such a case when one becomes necessary
- Spot present-day gaps in safety strategy for model autonomy
- Pilot a process for internal and external review that could be used to validate such load-bearing cases in the future

## Focus Area: Sabotage

The report focuses on "sabotage" as the broad category of misaligned behaviors that, unlike hallucination, poses distinct emerging risks at high capability levels that can be difficult to respond to without significant preparation.

## Review Process

This exercise included multiple rounds of revision in cooperation with:
- **Internal Review:** Anthropic's Alignment Stress-Testing team
- **Independent Review:** METR (AI safety and evaluation nonprofit)

Both parties had access to additional evidence beyond what is presented in the report and prepared written reviews reflecting their degree of confidence in the report's conclusions. Both reviews ultimately endorse the assessment of risk level, though they raise doubts about argumentation and evidence in some places and suggest improvements for future reports.

### Review Outcomes

- Both reviewing teams largely agree with the core assessment
- Multiple ways have been identified for the report and safeguards to be improved
- The core report team does not endorse every concern raised in the reviews, with some productive disagreements on empirical and conceptual questions
- The report is being released as it currently exists rather than delaying for consensus on potentially thorny questions

## Model Assessment

The report focuses primarily on Claude Opus 4, which was Anthropic's most capable model when they started drafting the report, with only more limited discussion of subsequent models.

## Impact on Anthropic's Practices

This pilot exercise has led to substantive revisions in threat models and supported changes to Anthropic's alignment-related practices, including:
- Changes to model training oriented toward improving the faithfulness and monitorability of model reasoning

## Publication

**Report Documents Released:**
1. Anthropic's Summer 2025 Pilot Sabotage Risk Report
2. Alignment Stress-Testing Review
3. METR's Independent Review

## Important Notes

- This is a pilot exercise and future safety assessments along these lines will likely include both additional concrete safety measures and further refined argumentation
- This work represents Anthropic's transparent effort to show their work on addressing misalignment risks in deployed models
- The language and framing (risk report vs. affirmative case) emphasizes that Anthropic is not claiming to have achieved a specific pre-determined level of risk, but rather laying out what they see as the existing level of risk
