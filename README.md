# ISRO Placement Management Portal

A secure, multi-user web portal built during a Software Engineering internship at ISRO 
(Indian Space Research Organisation), designed to manage the placement process for 
Admin, Student, and Company users.

## Overview
This portal supports three distinct user roles with role-based access control, allowing 
each type of user to view and act only on data relevant to their responsibilities. It 
includes secure authentication, resume-based job matching, and real-time dashboards for 
tracking placement activity.

## Features
- **Role-Based Access Control (RBAC)** — separate permissions and views for Admin, 
  Student, and Company accounts
- **OTP-based Multi-Factor Authentication** — email verification via SMTP for 
  stronger login security
- **Resume-Matching Engine** — parses resume data and applies skill-matching logic 
  (TF-IDF based) to recommend suitable job roles to students
- **Interactive Dashboards** — real-time visibility into student profiles, 
  applications, and placement status for Admin and Company users
- **Secure Session Handling** — password hashing and protected session management

## Tech Stack
- **Backend:** Python, Flask
- **Database:** SQLite3
- **Frontend:** HTML, CSS, Jinja2 Templating
- **Auth:** SMTP-based OTP verification, password hashing
- **ML Component:** TF-IDF vectorization for resume-to-role matching
- **Deployment:** Render

## My Role
Contributed to the design and development of the authentication system, dashboard 
views, and resume-matching module as part of a Software Engineering internship, 
under mentor guidance, from Feb 2025 to Jul 2025.

## Note
This project was built as part of an academic internship at ISRO and reflects 
project-training work rather than an official ISRO production system.
