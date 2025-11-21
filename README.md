# SentriAI – Product Requirements Document (PRD)

## Product Overview

SentriAI is a lightweight, AI-driven system designed to identify students who are at risk of dropping out from school. The platform combines synthetic data, predictive scoring, and a simple admin dashboard to help schools intervene proactively.

**MVP simulates:**
- AI-generated predictions  
- Risk-level explanations  
- Alerts  
- Intervention suggestions  

Built using `Lovable`, `Glide/Airtable AI`, with optional `Figma` polish, SentriAI delivers both a functional prototype and visually compelling design assets.

---

## Problem Statement

Schools consistently lose students due to:
- Poor engagement
- Low attendance
- Academic decline
- Behavioral instability

Most institutions lack a simple, affordable tool to flag risk early and provide actionable recommendations.

**SentriAI solves this gap** by offering a low-code, fast-to-build AI simulation to demonstrate an early-warning system.

---

## Goals & Success Criteria

### Primary Goals
- Detect students with Low / Moderate / High dropout risk
- Give administrators visibility into risk trends
- Provide “reason for risk” and recommended interventions
- Show how AI supports student retention

### Success Indicators
- Working prototype with accurate simulated predictions
- Admin dashboard showing risk distribution & student profiles
- Clean landing page explaining system and value
- Presentation-ready visuals for demo or pitch

---

## Target Users

- Administrators  
- School administrators  
- Guidance counselors  
- Learning coordinators  

**Needs:** Visibility, clarity, proactive alerts

> _(Optional Future)_  
> Student & Parent Portals (not included in MVP)

---

## User Persona

**Name:** Mrs. Amaka Okorie  
**Role:** Student Affairs / School Administrator  
**Age:** 32–40  

**Background:**  
Manages attendance, academic reports, behavior logs, and parent communication for hundreds of students. Decisions are often manual and time-consuming.

**Goals:**
- Identify at-risk students early
- Monitor attendance, behavior, performance in one place
- Trigger timely interventions
- Improve student retention rates

**Pain Points:**
- Scattered data across systems
- Warning signs easy to miss
- Reactive rather than proactive intervention
- Difficulty tracking trends over time
- Relies on manual reviews and intuition

**Needs:**
- Clear risk scores
- Simple explanations for flagged students
- Unified dashboard
- Actionable recommendations

---

## Core Features (MVP)

### A. Landing Page
- Overview of the system
- How risk prediction works
- Call-to-action: "View Dashboard"

### B. Admin Dashboard
- Total students
- Risk distribution (Low/Moderate/High)
- Quick alerts
- High-risk students overview

### C. Student List
- Search & filter
- Risk category badges
- Key data points (attendance %, GPA, warnings, behavior score)

### D. Student Profile
- Personal details
- Attendance trend
- GPA history
- Behavioral score timeline
- AI-generated risk level
- Explanation for prediction (e.g., “attendance dropped 20%, GPA declined”)

### E. Risk Score Breakdown
- Contribution factors
- Weightings
- Risk trend over time

### F. Alerts Center
- Students crossing risk thresholds
- Behavior spikes
- Sudden drops in performance

### G. Intervention Suggestions
- Personalized action recommendations
- Parent engagement steps
- Academic support strategies
- Follow-up reminders

---

## Workflow / Solution Approach

1. **Simulation + Design Blueprint**
    - Generate rough UI with Lovable
    - Mock screens: landing page, dashboard, lists, profiles, alerts
    - Blueprint before real prototyping

2. **Create Synthetic Dataset**
    - Fields: Attendance %, GPA, Behavioral score, Warning count, Parent engagement, Historical trends, Risk level (Low/Moderate/High)
    - Tools: Mockaroo / ChatGPT table generator

3. **Build AI Prediction Logic**
    - Tools: Glide AI, Airtable AI, or Make
    - Flow: Upload synthetic CSV → AI field predicts risk → Output explanation and score → Export sample predictions

4. **Prototype in Lovable**
    - Inputs: Synthetic dataset, AI prediction outputs, simulation screens
    - Lovable handles: App generation, UI, routing, data display, basic rule logic

5. **Final Figma Polish (Optional)**
    - Import Lovable screens
    - Enhance: Spacing, color, typography
    - Prepare pitch visuals

6. **Week 1 Deliverables**
    - Interactive web app
    - Polished Figma mockups
    - Landing page
    - Predictive simulation
    - Dashboard and student profiles
    - Shareable demo link

7. **Non-Goals (MVP Scope)**
    - Real machine learning model
    - Real student data
    - Live SMS/email notifications
    - Student/parent login
    - Mobile app

---

## Risks & Mitigations

| Risk                            | Mitigation                                  |
|----------------------------------|---------------------------------------------|
| AI predictions may be inconsistent | Fix dataset ranges, standardize prompts      |
| Over-complexity                   | Limit MVP to admin only                     |
| Visual clutter                    | Polish UI in Figma                          |
| Data realism issues               | Enhance dataset with historic trends        |

---

## Tech Stack

- Lovable – Web app generation
- Airtable AI / Glide AI – Prediction engine
- Figma – Visual polish & pitch design
- ChatGPT / Mockaroo – Synthetic data

---

## Quotes & Additional Notes

> "If I could easily see who needs intervention this week, I’d make fewer manual mistakes and improve student outcomes. But tools are expensive unless you prove the concept first."
