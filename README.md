# Cheerio GTM Use-Case Mapper

An evidence-first GTM intelligence prototype for identifying potential customer-workflow opportunities for Cheerio AI.

## Problem

Cheerio AI supports different customer-engagement workflows across D2C, BFSI, Real Estate, and Healthcare.

The GTM challenge is not simply finding companies or checking whether they use WhatsApp.

The challenge is understanding:

- How the customer journey works
- What communication channels are already used
- What is already automated
- Where workflow complexity exists
- Where potential gaps may exist
- Which Cheerio use case could be relevant

## What I Built

A Clay-based research workflow that moves from:

Company Discovery
→ Data Validation
→ Customer Journey Research
→ Existing Capability Research
→ Workflow Gap Identification
→ Cheerio Use-Case Hypothesis

## Research Scope

Started with **50 companies across 4 verticals**.

| Vertical | Companies Found | Removed During Validation | Clean Prospect Pool | Deep Research |
|---|---:|---:|---:|---:|
| D2C / E-commerce | 15 | 0 | 15 | 3 |
| BFSI | 15 | 6 | 9 | 3 |
| Real Estate | 10 | 0 | 10 | 3 |
| Healthcare | 10 | 3 | 7 | 3 |
| **Total** | **50** | **12** | **41** | **12** |

### Data Validation

Companies were removed when the returned location/geography did not match the intended India-focused research scope.

This produced a **38-company clean prospect pool**.

## AI Research

Instead of enriching all 38 companies immediately, I tested the research methodology on **3 companies per vertical (12 total)**.

### D2C / E-commerce

Custom AI research columns:

- `WhatsApp Channel Usage`
- `Customer Journey`

Focus:
**Product discovery → conversational engagement → commerce**

### BFSI

Custom AI research:

- `BFSI Customer Engagement`

Focus:
**Customer lifecycle → communication → follow-up → retention**

### Real Estate

Custom AI research:

- `Real Estate Customer Engagement`

Focus:
**Lead/inquiry → sales communication → follow-up → booking → post-sale**

### Healthcare

Custom AI research:

- `Healthcare Engagement & Retention Workflow`

Focus:
**Patient/customer inquiry → service/order → communication → follow-up → retention**

## Research Philosophy

The prototype intentionally separates:

**Observed**
What can be verified from public evidence.

**Not Found**
What could not be verified publicly.

**Hypothesis**
A potential opportunity that requires validation.

Existing technology adoption is not treated as a negative signal.

For example:

`WhatsApp = Yes`

does not automatically mean:

`Cheerio Opportunity = Low`

The business workflow and potential friction must be understood first.

## Key Learnings So Far

### 1. Industry alone does not define the use case

D2C, BFSI, Real Estate, and Healthcare have different customer journeys and therefore require different research signals.

### 2. Existing automation does not eliminate opportunity

Companies such as Gera Developments, smallcase, and RazorMetrics already have significant automation.

The question becomes whether there is an incremental workflow opportunity.

### 3. Public evidence has limits

A missing feature on a public website does not prove that the company does not have that capability internally.

Therefore:

`Not publicly observed ≠ Does not exist`

### 4. Clay data requires validation

The initial 50-company search produced geographic mismatches.

**12 companies were removed**, leaving a cleaner **38-company research pool**.

## Tech Stack

- **Clay** — company discovery, enrichment and AI research
- **AI** — customer-journey and workflow analysis
- **Public web data** — evidence collection

## Current Status

**Phase 1 — Complete**

- 50 companies discovered
- 38 companies retained after validation
- 12 companies deeply researched
- 4 vertical-specific research approaches tested

### Next

- Compare the 12 researched companies
- Develop preliminary ICP hypotheses
- Identify repeatable opportunity signals
- Build an opportunity-scoring framework
- Map prospects to relevant Cheerio workflows
