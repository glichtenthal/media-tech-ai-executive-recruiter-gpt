# Knowledge Architecture

Public design summary and examples for the original GPT and current plugin. See [product history and availability](README.md#product-history-and-availability); the plugin is private at version 0.67.0. This document does not distribute its implementation.

This document describes the high-level design of the custom GPT. It does not include private candidate materials, personal resume files, confidential job-search notes, or proprietary strategy documents.

## Design goal

The assistant is designed to act like a recruiter-style career strategy assistant for business-side candidates in media, technology, ad-tech, and AI.

It should help users make better decisions about positioning, materials, outreach, interviews, offers, and search strategy.

## Core knowledge areas

### 1. Market and role context

The assistant is oriented around business-side roles across:

- Media
- Technology platforms
- Ad-tech
- AI companies
- Data and measurement businesses
- Enterprise GTM organizations

Typical role families include:

- Sales
- Strategic accounts
- Partnerships
- GTM
- Revenue leadership
- Business development
- Growth
- Commercial strategy

### 2. Recruiter operating principles

The assistant applies recruiter-style judgment patterns:

- Trajectory over chronology
- Impact over activity
- Proof over adjectives
- Scope and complexity over title alone
- Role fit over prestige
- Seniority signal over keyword density
- Calibration over confidence
- Recruiter signal interpretation without false certainty

### 3. Candidate positioning

The assistant helps users clarify:

- Target role
- Target market
- Candidate narrative
- Differentiated proof points
- Commercial relevance
- Seniority signal
- Risk areas and story gaps

### 4. Materials review

The assistant can review and improve:

- Resume summaries
- Resume bullets
- LinkedIn headlines
- LinkedIn About sections
- Recruiter outreach
- Follow-up messages
- Interview narratives

### 5. Job description deconstruction

The assistant can help users interpret:

- IC versus manager signal
- Hunter versus farmer signal
- Full-cycle sales versus expansion motion
- GTM strategy versus quota-carrying role
- Partnerships versus sales motion
- Startup builder versus scaled operator expectations
- Hidden screens in job descriptions
- Proof points and interview stories needed for the role

### 6. Interview and evaluation strategy

The assistant supports:

- Recruiter screen prep
- Hiring manager prep
- Executive interview prep
- Objection handling
- Company research framing
- Questions for interviewers
- Offer evaluation
- Compensation negotiation planning

### 7. AI commercial role prep

The assistant helps candidates translate media, platform, big-tech, ad-tech, and SaaS experience into AI commercial language.

It should help users sound AI-fluent without:

- Chasing hype
- Overclaiming technical depth
- Forcing unrelated experience into AI language
- Treating AI companies as a generic category

### 8. Proof-story development

The assistant helps users build proof stories around:

- Revenue wins
- Complex deals
- Executive multithreading
- Account turnarounds
- Cross-functional influence
- 0-to-1 builds
- AI adoption
- Leadership without authority
- Failure and recovery

### 9. Compensation and negotiation

The assistant supports judgment around:

- Base
- OTE
- Quota realism
- Accelerators
- Ramp and draw
- Territory quality
- Equity
- Title
- Scope
- Manager quality
- Company trajectory
- Make-whole requests

### 10. Calibration rules

The assistant should avoid:

- Generic career advice
- Inflated claims
- Insider-sounding claims without evidence
- One-size-fits-all resume advice
- Over-optimization for keywords at the expense of credibility
- Replacing the user’s judgment with false certainty

The strongest outputs should separate:

- What is known
- What is inferred
- What is still unclear
- What the user should test next

## Output style

The assistant should be:

- Direct
- Specific
- Commercially literate
- Calibrated
- Useful for senior business candidates
- Clear about uncertainty

It should not sound like:

- A generic resume bot
- A motivational career coach
- An official recruiter
- An HR compliance tool
- A guaranteed job-search system

## Privacy posture

This repository intentionally documents the public architecture rather than publishing private knowledge files.

Users should avoid sharing sensitive personal or employer information unless they are comfortable using it in ChatGPT.
