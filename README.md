# Internship Placement Analytics Dashboard

An interactive Tableau dashboard for analyzing internship placement performance across students, companies, roles, and applications.

## Tableau Public Dashboard

Live Dashboard: https://public.tableau.com/views/InternshipPlacementAnalyticsDashboard/Dashboardhome?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Project Overview

This dashboard helps an Internship Cell monitor student participation, company engagement, role demand, recruitment funnel efficiency, offer outcomes, and placement performance.

## Dashboard Pages

1. Landing Page
2. Executive Summary
3. Student & Company Analytics
4. Role & Recruitment Funnel Analytics

## Dataset

The dataset is synthetically generated for academic/demo purposes.

- Students: 315
- Companies: 325
- Roles: 810
- Applications: 62,000

## Tools Used

- Tableau Desktop
- Tableau Public
- CSV Dataset

## Key Features

- KPI cards for placement overview
- Department-wise and industry-wise analysis
- Student and company analytics
- Recruitment funnel tracking
- Role demand and stipend analysis
- Interactive filters and navigation buttons

## Data Model

- Students.student_id is related to Applications.student_id
- Roles.role_id is related to Applications.role_id
- Companies.company_id is related to Roles.company_id
