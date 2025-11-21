
Product Requirements Document (PRD)  SentriAI.


Product Overview

SentriAI is a lightweight AI-driven system designed to identify students who are at risk of dropping out from school. The platform combines synthetic data, predictive scoring, and a simple admin-facing dashboard to help schools proactively intervene before disengagement escalates.

The MVP simulates:

AI-generated predictions

Risk-level explanations

Alerts

Intervention suggestions


Built using Lovable, Glide/Airtable AI, and optional Figma polish, the system delivers both a functioning prototype and visually compelling design assets.



Problem Statement

Schools consistently lose students due to:

Poor engagement

Low attendance

Academic decline

Behavioral instability


But most institutions lack a simple, affordable tool that flags risk early and gives actionable recommendations.

SentriAI solves that gap by providing a low-code, fast-to-build AI simulation to demonstrate how early-warning systems work.



Goals & Success Criteria

Primary Goals

Detect students with Low / Moderate / High dropout risk.

Give administrators clear visibility into risk trends.

Provide “reason for risk” and recommended interventions.

Demonstrate how AI can support student retention.


Success Indicators

Working prototype that displays accurate simulated predictions.

Admin dashboard showing risk distribution and student profiles.

Clean landing page explaining the system and value.

Presentation-ready visuals for demo or pitch.



Target Users

Admin

School administrators

Guidance counselors

Learning coordinators

Needs: visibility, clarity, proactive alerts.


(Optional Future) Student + Parent Portals

Not included in MVP.



User Persona

Name: Mrs. Amaka Okorie
Role: Student Affairs / School Administrator
Age: 32–40

Background:
Manages attendance, academic reports, behaviour logs, and parent communication for hundreds of students. Decisions are often manual and time-consuming.

Goals:

Identify at-risk students early

Monitor attendance, behaviour, and performance in one place

Trigger timely interventions

Improve student retention rates


Pain Points:

Scattered data across multiple systems

Early warning signs are easy to miss

Reactive intervention instead of proactive

Difficulty tracking trends over time

Relies on manual reviews and intuition


Needs:

Clear risk scores

Simple explanations for each flagged student

Unified dashboard

Actionable intervention recommendations


Quote:
“Show me which students need attention now — and why.”



Core Features (MVP)

A. Landing Page

Overview of the system

How risk prediction works

Call-to-action to “View Dashboard”


B. Admin Dashboard

Total students

Risk distribution (Low/Moderate/High)

Quick alerts

High-risk students overview


C. Student List

Search & filter

Risk category badges

Key data points (attendance %, GPA, warnings, behavior score)


D. Student Profile

Personal details

Attendance trend

GPA history

Behavioral score timeline

AI-generated risk level

Explanation for prediction (“because attendance dropped 20%, GPA declined, etc.”)


E. Risk Score Breakdown

Contribution factors

Weightings

Risk trend over time


F. Alerts Center

Students crossing risk thresholds

Behavior spikes

Sudden drops in performance


G. Intervention Suggestions

Personalized action recommendations

Parent engagement steps

Academic support strategies

Follow-up reminders




Workflow / Solution Approach

1. Simulation + Design Blueprint

Generate rough UI using Lovable

Produce mock screens: landing page, dashboard, lists, profiles, alerts, etc.

Treat this as the blueprint before real prototyping.


2. Create Synthetic Dataset

Data fields:

Attendance %

GPA

Behavioral score

Warning count

Parent engagement

Historical trends

Final risk level (Low/Moderate/High)


Tools:

Mockaroo OR ChatGPT table generator.


3. Build AI Prediction Logic

Tools: Glide AI, Airtable AI, or Make.

Flow:

Upload synthetic CSV

Use AI field to predict risk

Output explanation + numerical score

Export sample predictions as JSON/CSV


4. Build Prototype in Lovable

Inputs:

Synthetic dataset

AI prediction outputs

Initial simulation screens


Lovable handles:

App generation

UI structure

Routing

Display of data

Simple rule logic


5. Final Figma Polish (Optional)

Import Lovable screens

Enhance spacing, color, typography

Prepare pitch-ready visuals


6. Week 1 Deliverables

Interactive web app

Polished Figma mockups

Landing page

Predictive simulation

Dashboard + student profiles

Shareable demo link



7. Non-Goals (Out of Scope for MVP)

Real machine learning model

Real student data

Live SMS/email notifications

Student/parent login

Mobile app



Risks & Mitigations

Risk
Mitigation 
AI predictions may be inconsistent
Fix dataset ranges and standardize prompts
Over-complexity
Keep MVP limited to admin only
Visual clutter
Use Figma for final polish
Data realism issues
Enhance dataset with historical trends

	


Tech Stack

Lovable – Web app generation

Airtable AI / Glide AI – Prediction engine

Figma – Visual polish & pitch design

ChatGPT / Mockaroo – Synthetic data




Team Members 

 1. Ruth Igwe-Oruta 
2.  Maureen Cheptoo
3. Olatunji Abdulraheem
4. Idara Akpan
5. Akpakpa Rukevwe Mary
6. Asheson Enneh
7. ⁠Eno Peters
8. ⁠Vivian Ibeawuchi
9. ⁠Nissi Marshall
10. Precious Babalola
11. Ja'afar Umar AI-Jenewy
12. Gold Sani
