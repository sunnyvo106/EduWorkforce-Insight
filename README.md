📊 School Workforce Planning & Visibility Platform (Stage 1 Pilot)
🧩 Product Overview

The School Workforce Planning & Visibility Platform is a school-facing workforce analytics solution funded by the Ministry of Education (MOE) to improve workforce planning visibility and reduce operational decision delays in secondary schools.

The platform centralises fragmented workforce data across existing systems (HR, payroll, timetable, leave management) into a consolidated reporting layer to enable timely staffing decisions.

This Stage 1 pilot focuses on improving reliever hiring responsiveness and reducing manual reporting burden.

🎯 Problem Statement

Workforce data in schools is currently distributed across multiple independent systems (HR, payroll, timetable, leave), with no central reporting layer or integration capability.

As a result:

Leadership lacks timely visibility of workforce allocation and vacancy duration.

Decisions to hire additional relievers are delayed.

Instructional continuity is disrupted.

Workforce reports require manual consolidation across systems.

The absence of centralised visibility leads to reactive rather than proactive workforce planning.

📉 Current State Challenges
Issue	Operational Impact
Fragmented workforce data	Delayed staffing decisions
No central reporting layer	Manual report preparation
Limited visibility of vacancy duration	Prolonged unfilled roles
No consolidated workload view	Uneven department load
🎯 Business Objectives
Objective 1

Reduce reliever hiring approval turnaround time from 7 days to 3 days to improve instructional continuity and minimise class disruption.

Objective 2

Reduce manual workforce reporting preparation time from 6 hours to 2 hours per month through centralised workforce data visibility.

📌 Scope (Stage 1 Pilot)
In Scope

Single-campus secondary school pilot

Centralised workforce reporting dashboard

Vacancy duration visibility

Workforce allocation visibility (department-level)

Reliever hiring workflow visibility

Monthly reporting export

Out of Scope

Multi-campus schools

Predictive attrition modelling

Individual teacher wellbeing tracking

Replacement of existing HR/payroll/timetable systems

National deployment

👥 Stakeholders
Role	Responsibility
Ministry of Education (Sponsor)	Funding & governance oversight
Principal (Primary User)	Workforce decision-making
HR / Business Manager	Data validation & reporting
Board of Trustees	Oversight & reporting consumer
📊 Key Performance Indicator

Primary KPI:

Reliever Hiring Approval Turnaround Time
Baseline: 7 days
Target: 3 days

Secondary KPI:

Manual Workforce Reporting Preparation Time
Baseline: 6 hours/month
Target: 2 hours/month

🏗 Proposed Solution (Stage 1)

A centralised workforce visibility dashboard that integrates data from:

HR system

Payroll system

Timetable system

Leave management system

The platform will provide:

Vacancy duration tracking

Workforce allocation by department

Reliever request visibility

Automated monthly reporting

The system will function as a reporting and visibility layer only and will not replace operational systems.

🚀 Future Roadmap (Phase 2 – Not in Scope)

Predictive attrition risk modelling

Regional multi-school dashboard

Geographic workforce heatmaps

Automated early-warning staffing alerts

**Business Requirements Document (BRD)**
Stage 1 Pilot – School Workforce Visibility Platform
1. Executive Summary

EduWorkforce Insight is a conceptual school-level workforce visibility platform designed to improve staffing decision-making through centralised data consolidation.

The Stage 1 pilot focuses on reducing reliever hiring decision delays and minimising manual workforce reporting effort by introducing a unified reporting layer built on existing operational systems.

This document outlines the business problem, objectives, scope, stakeholders, high-level requirements, and architectural direction.

2. Background

Research across public education reports, workforce data, and sector discussions revealed recurring operational patterns:

Workforce data stored across disconnected systems

Delayed visibility of staffing allocation

Manual report consolidation processes

Reactive reliever hiring decisions

Rather than addressing systemic policy or funding issues, this project focuses on operational visibility improvement within existing infrastructure.

3. Business Problem

Workforce data across HR, payroll, timetable, and leave systems currently operates in silos without a central reporting layer.

This fragmentation results in:

Delayed reliever hiring decisions

Limited visibility of vacancy duration

Uneven workload allocation visibility

Manual report consolidation requiring 6+ hours per month

These limitations increase instructional disruption risk and operational inefficiency.

4. Business Objectives
Objective 1

Reduce reliever hiring approval turnaround time from 7 days to 3 days to improve instructional continuity and minimise class disruption.

Objective 2

Reduce manual workforce reporting preparation time from 6 hours to 2 hours per month through centralised workforce visibility.

5. Scope
5.1 In Scope – Stage 1 Pilot

Single-campus secondary school deployment

Consolidated workforce reporting dashboard

Vacancy duration tracking

Workforce allocation visibility by department

Reliever hiring workflow visibility

Automated monthly reporting

Daily data refresh from source systems

5.2 Out of Scope

Predictive attrition modelling

Teacher wellbeing tracking

Replacement of HR, payroll, or timetable systems

Multi-campus or national deployment

Real-time integration architecture

6. Stakeholders
Role	Responsibility
Ministry of Education	Project Sponsor
Principal	Primary User
HR / Business Manager	Operational User
Board of Trustees	Reporting Consumer
7. Key Performance Indicators (KPIs)
KPI	Baseline	Target
Reliever Hiring Approval Turnaround	7 days	3 days
Manual Workforce Reporting Time	6 hrs/month	2 hrs/month
8. High-Level Business Requirements

The system must provide consolidated visibility of workforce allocation across departments.

The system must provide visibility of vacancy duration.

The system must track reliever hiring approval timelines.

The system must generate automated monthly workforce reports.

The system must integrate workforce data from existing HR, payroll, and timetable systems.

9. High-Level Architectural Direction

The solution will function as a read-only visibility layer.

Data will be:

Extracted daily from existing operational systems

Transformed into a standardised workforce schema

Loaded into a central cloud-based data warehouse (NZ data residency)

Presented through a leadership dashboard

The system will not modify or replace operational systems.

Detailed technical specifications will be documented in the System Requirements Specification (SRS).

10. Future Roadmap (Not in Scope for Stage 1)

Predictive attrition modelling

Multi-school regional dashboard

Geographic workforce heatmaps

Automated staffing risk alerts
