# Cheerio GTM Use-Case Mapper

An evidence-first GTM intelligence prototype for identifying potential customer-workflow opportunities for Cheerio AI.

## Problem

Cheerio AI supports different customer engagement and communication workflows across industries.

The GTM challenge is not simply finding companies or checking whether they use WhatsApp.

The goal is to understand:

- How the customer journey works
- What communication channels are already used
- What is already automated
- Where workflow complexity exists
- Where potential workflow gaps may exist
- Which Cheerio use case could be relevant

## What I Built

A Clay-based GTM research workflow:

Company Discovery
→ Data Validation
→ Industry-Specific Research
→ Customer Journey Mapping
→ Workflow Assessment
→ Opportunity Scoring
→ ICP Hypothesis

## Research Scope

An initial prospect universe of **50 companies** was created across four verticals.

| Vertical | Initial Companies | Removed | Research Sample |
|---|---:|---:|---:|
| D2C / E-commerce | 15 | 0 | 3 |
| BFSI | 15 | 6 | 3 |
| Real Estate | 10 | 0 | 3 |
| Healthcare | 10 | 3 | 3 |
| **Total** | **50** | **9** | **12** |

The 50-company universe was used for prospect discovery and validation.

**The MVP deep-research sample contains 12 companies — 3 randomly selected companies per vertical.**

The remaining companies were intentionally not researched further for this MVP.

## Research Method

### 1. Company Discovery

Clay was used to identify companies across:

- D2C / E-commerce
- BFSI
- Real Estate
- Healthcare

### 2. Data Validation

Companies returned outside the intended India-focused research scope were removed.

**50 discovered → 41 retained**

### 3. Representative Research Sample

Rather than deeply researching all 41 companies, **3 companies were randomly selected from each vertical**.

**4 verticals × 3 companies = 12 companies**

This sample was used to test the GTM research methodology and scoring framework.

## Industry-Specific Research

Research was customized by vertical based on Cheerio's documented use cases.

### D2C / E-commerce

Research signals:

- WhatsApp Channel Usage
- Customer Journey

Focus:

Product discovery → conversational commerce → purchase → repeat engagement

### BFSI

Research signal:

- BFSI Customer Engagement

Focus:

Customer lifecycle → communication → follow-up → retention

### Real Estate

Research signal:

- Real Estate Customer Engagement

Focus:

Lead/inquiry → communication → follow-up → booking → post-sale

### Healthcare

Research signal:

- Healthcare Engagement & Retention Workflow

Focus:

Patient/customer inquiry → service/order → follow-up → retention

## GTM Opportunity Signals

The research was synthesized into seven signals:

1. Journey Complexity
2. Communication Intensity
3. Channel Fragmentation
4. Critical Business Event
5. Automation Maturity
6. Workflow Friction
7. Research Confidence

The first five relevant signals were used to construct the opportunity score.

Automation Maturity and Research Confidence were retained as context rather than direct score components.

## Opportunity Scoring

A deterministic **100-point GTM Opportunity Score** was created.

| Signal | Weight |
|---|---:|
| Journey Complexity | 25 |
| Communication Intensity | 20 |
| Channel Fragmentation | 15 |
| Critical Business Event | 25 |
| Workflow Friction | 15 |
| **Total** | **100** |

Research Confidence is tracked separately.

### Scoring principle

Existing automation is not treated as a negative signal.

The hypothesis is that opportunity may exist in coordinating complex workflows across existing systems, channels, and human teams.

## MVP Results

### Opportunity Scores

| Vertical | Company 1 | Company 2 | Company 3 | Average |
|---|---:|---:|---:|---:|
| D2C | 72 | 67 | 72 | 70.3 |
| BFSI | 75 | 92 | 92 | 86.3 |
| Real Estate | 84 | 97 | 92 | 91.0 |
| Healthcare | 95 | 89 | 87 | 90.3 |

**Sample range: 67–97**

Within this 12-company research sample, Real Estate and Healthcare produced the highest average opportunity scores, followed by BFSI and D2C.

This is an initial research observation, not proof that one vertical is definitively a better ICP.

## Key Findings

### 1. WhatsApp presence alone is not a strong ICP signal

Many researched companies already use WhatsApp or other communication channels.

Technology adoption does not automatically determine GTM fit.

### 2. Workflow complexity appears more useful

The strongest recurring pattern was:

**Complex journey + repeated communication + multiple touchpoints + measurable business event**

### 3. Existing automation does not eliminate opportunity

Several high-scoring companies already have significant automation.

The potential opportunity may be orchestration across existing workflows rather than basic automation.

### 4. Business events matter

The researched workflows were connected to measurable events such as:

- Purchase
- Investment
- Loan funding
- Booking
- Appointment
- Enrollment
- Fulfillment
- Retention

### 5. Public evidence has limitations

"Not publicly observed" is not treated as:

"Does not exist."

Workflow gaps are therefore treated as hypotheses requiring validation.

## Preliminary ICP Hypothesis

Cheerio may be most relevant to customer-facing businesses with **high-volume, multi-step customer journeys**, where communication occurs across multiple channels and stakeholders, and where better workflow orchestration can influence a measurable business event such as purchase, booking, application, enrollment, fulfillment, or retention.

**Status: Initial hypothesis based on a 12-company research sample.**

## Tech Stack

- **Clay** — company discovery, enrichment and workflow automation
- **AI research** — customer journey and workflow analysis
- **Public web data** — evidence collection

## Current Status

### MVP Complete

- 50 companies discovered
- 41 retained after geographic validation
- 12 companies selected for deep research
- 4 vertical-specific research approaches tested
- 7 GTM opportunity signals defined
- 100-point opportunity scoring model implemented
- Initial ICP hypothesis developed

### Next Phase

- Validate the ICP hypothesis with additional accounts
- Refine opportunity signals based on observed outcomes
- Map high-opportunity accounts to specific Cheerio workflows
- Test whether the scoring model predicts genuine GTM opportunities
