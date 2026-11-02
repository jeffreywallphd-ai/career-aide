# career aid
A system to help students prepare for, navigate, and follow up on career fairs

Michigan Technological University
MIS 4000 Career Aid Project
Fall 2026, as of 10/7/2026


TABLE OF CONTENTS
--------------------------------------------------------------------------------
  1. Project Overview
  2. Problem Statement
  3. Goals and Objectives
  4. Target Market
  5. Scope and Boundaries
  6. Key Features
  7. Technologies Utilized
  8. Major Milestones
  9. Guardrails (Accuracy, Privacy, Accessibility)
 10. Installation Instructions
 11. Team Members and Developers
 12. Supporting Project Documents


## 1. PROJECT OVERVIEW
--------------------------------------------------------------------------------
Career Aid is a proposed, Michigan Tech-specific career readiness platform. It
helps students prepare for, navigate, and follow up on the university career
fair and related career events, from any device.

Rather than replacing Handshake, Career Aid acts as a customized experience
layer for the Michigan Tech community. It fills gaps that a national SaaS
product cannot address: venue-level navigation, validated employer data,
eligibility-aware filtering, and personal tracking of employer contacts.

The career fair is a high-stakes, time-limited event. In Fall 2025 it included
roughly 4,100 students, 357 registered employers, 388 tables, and 1,010
recruiters, all within a five-hour window. Career Aid is designed to help each
student spend those five hours well.

Planned products in the portfolio:

  - An Employer Relationship Management tool (career fair contact tracker)
  - A 2D interactive career fair map and navigation tool
  - An opportunity discovery and filtering tool (major, skills, eligibility)
  - A career events awareness feed
  - A personalized dashboard and AI-assisted career / degree plan

Portfolio vision statement (draft):

  "A Michigan Tech where every student, regardless of major, background, or
  experience, can find and act on the right career opportunities with
  confidence, through a connected set of career tools tailored to the campus."


## 2. PROBLEM STATEMENT
--------------------------------------------------------------------------------
The career fair experience is difficult to prepare for, hard to navigate, and
poorly supported afterward. Handshake tools only help so much.

  - Students must strategize under time pressure: which companies to visit,
    which are relevant to their major, where to go next, and what to say to
    each recruiter.
  - The current system relies on employer-entered metadata. Employers can miss
    class year, job types, or work authorization, and university staff must
    review registrations by hand. Errors lead students to spend time on the
    wrong employers.
  - Employers cast a wide net with "All Majors" but interview only a select
    few in person, so listings may not reflect real hiring priorities.
  - Handshake does not specify which floor a booth is on, and the depth of
    employer information varies.
  - Participation is uneven. The fair leans heavily toward engineering and
    computing. Business and Sciences & Arts trail, and forestry /
    environmental science students engage the least.
  - Of 357 registered employers in Fall 2025, 210 were in manufacturing (89),
    civil (67), and construction (54). Rigid engineering labels make
    cross-disciplinary applications hard for other majors to see.
  - International students face extra eligibility questions and misinformation
    that can make the fair a demoralizing experience.
  - Transfer, first-year, and first-generation students vary widely in their
    understanding of the unspoken rules of career fairs.
  - Post-fair follow-up is dated: students write down who they spoke with and
    what was discussed, wait for interviews, and send follow-up emails with no
    tool support.
  - Information about Career Services events, employer sessions, and local or
    external networking events is scattered.

Evidence gathered so far:

  - Fall 2025 career fair statistics (attendance, employers, tables,
    recruiters, industry mix)
  - Competitor review of Handshake showing data gaps, no employer validation,
    and limited end-user customization
  - A concept prototype of the Employer Relationship Management tracker
  - No student survey results are documented yet


## 3. GOALS AND OBJECTIVES
--------------------------------------------------------------------------------
Primary goal:
  Give Michigan Tech students a customized, accurate, easy-to-use way to
  prepare for, navigate, and follow up on career fairs and career events.

Objectives:
  1. Improve awareness of Career Services programming, employer sessions, and
     local and external networking events.
  2. Make career fair navigation easier with a detailed 2D map, including
     floor and booth location, for the Student Development Complex (SDC).
  3. Improve opportunity data quality through employer data validation.
  4. Improve opportunity availability and clarity for international students
     by filtering on work authorization, visa sponsorship, and eligibility.
  5. Give each student a personalized dashboard, career plan, and
     skill-building guidance.
  6. Let students track which employers they contacted, what was discussed,
     and who they spoke with, and support follow-up afterward.
  7. Help students in non-engineering majors discover cross-disciplinary
     opportunities.
  8. Provide accessibility information so every student can plan their visit.
  9. Generate insight into why some colleges use the career fair less than
     others.
 10. Deliver faster by limiting scope to Michigan Tech rather than building a
     national-level platform.

Upstream strategy alignment:
  Career Aid supports the university's student career outcomes and career fair
  effectiveness. Detailed alignment is to be completed with the Portfolio Vision
  Worksheet.


## 4. TARGET MARKET
--------------------------------------------------------------------------------
Primary users
  - Current Michigan Tech students. Within this audience, the most underserved
    segments are:
      * International students, who need work authorization and visa
        sponsorship clarity
      * First-year students, who lack experience with career fairs
      * Transfer students, who must learn campus resources quickly
      * First-generation students, who may not know the unspoken rules
      * Students in colleges with lower engagement (Business, Sciences & Arts,
        Forestry / Environmental Science)
      * Students who need venue accessibility information

Secondary users
  - Career Services staff, who currently review employer registrations by hand
    and would benefit from better data quality.
  - Employers and recruiters, who benefit from better-matched student
    conversations and a communication channel.

Future market
  - Other universities seeking a campus-specific alternative to national career
    platforms, if the design proves portable.

Not the target market
  - National-level job seekers. Career Aid is intended for Michigan Tech
    students and campus career opportunities.

Competitive context (summary):
  Handshake is a national SaaS product. Career Aid differentiates on:
    - Customization for the end user
    - Detailed 2D venue map and navigation
    - Eligibility-aware filtering (work authorization, visa sponsorship)
    - Employer data validation
    - Contact tracking during the fair
    - Dashboard and skill-building plan
    - Faster delivery through a smaller, campus-specific scope


## 5. SCOPE AND BOUNDARIES
--------------------------------------------------------------------------------
In scope
  - Michigan Tech career fair preparation, navigation, and follow-up
  - Career events awareness (Career Services, employer sessions, local and
    external networking events)
  - Employer contact tracking and checklists
  - 2D map and navigation for the SDC venue
  - Opportunity filtering by major, skills, employer, skill plan, and
    eligibility
  - Employer data validation workflow
  - Communication between students and employers
  - Accessibility information

Out of scope (deliberate boundaries, draft)
  - Not a national job board or a replacement for Handshake
  - Not a system of record for hiring decisions
  - Not an applicant tracking system for employers
  - Not a decision-maker on a student's career path; it supports their choices
  - Not a marketing or recruiting channel for employers outside the career
    fair community


## 6. KEY FEATURES
--------------------------------------------------------------------------------
Employer Relationship Management (concept prototype built)
  - Checklist of employers with target flags
  - Fields for disciplines, topics discussed, and people talked to
  - Overall progress indicator
  - General conversation topics to ask recruiters (e.g., intern hiring volume,
    year-over-year changes, skills sought that are scarce internally)

Navigation (planned)
  - Detailed 2D map of the career fair venue
  - Floor and booth location for each employer
  - Accessibility information

Opportunity discovery (planned)
  - Filtering by major, skills, employer, and skill plan
  - Eligibility filtering: work authorization, visa sponsorship, and other
    requirements
  - Cross-disciplinary views so non-engineering majors can see relevant
    employers

Personalization (planned)
  - AI-assisted degree plan / career plan generation
  - Dashboard for opportunities and skill-building

Events and follow-up (planned)
  - Career events awareness feed
  - Post-fair follow-up support (notes, reminders, follow-up emails)

Staff and employer tools (planned)
  - Employer data validation to reduce manual staff review
  - Communication platform spanning employers and students


## 7. TECHNOLOGIES UTILIZED
--------------------------------------------------------------------------------
Note: Final technology choices have not been made. Items below are either
named in project documents or described by type.

Named solutions
  - Handshake (reference platform and possible data source)
  - Slide deck and word-processing tools used for the proposal and prototype

Front end and design
  - Web-based application for student use (mobile-friendly)
  - Dashboard and progress-tracking interface
  - 2D indoor mapping / floor-plan navigation component
  - Accessibility features aligned with common web accessibility standards

Data and back end
  - Back-end application and database for employer, event, and student data
  - Data validation and data quality tooling for employer-submitted records
  - Filtering and search engine for opportunities

AI
  - AI / machine learning component for degree plan and career plan generation

Security and communication
  - Authentication and role-based access control (student, employer, staff)
  - Communication / notification component (e.g., email or in-app messaging)


## 8. MAJOR MILESTONES
--------------------------------------------------------------------------------
Target dates have not been set in the project documents. Status below reflects
the work documented so far; update dates as the team schedules them.

Completed / documented
  [x] M1. Problem research and career fair observations
          (Fall 2025 statistics, student experience pain points)
  [x] M2. Opportunity statement and competitor / niche analysis
  [x] M3. Career Aid proposal presentation
  [x] M4. Employer Relationship Management concept prototype

Upcoming
  [ ] M5. Portfolio vision and theme approval
          (Portfolio Vision Worksheet completed)
  [ ] M6. Requirements gathering
          (students, Career Services staff, and employers; define data sources
          and eligibility fields)
  [ ] M7. System design
          (architecture, data model, and user experience mockups)
  [ ] M8. Core build
          (contact tracker, opportunity filtering, event awareness feed)
  [ ] M9. Venue map and navigation
          (2D SDC map and accessibility information)
  [ ] M10. Personalization
          (dashboard, skill plan, AI-assisted plan generation)
  [ ] M11. Employer data validation workflow and communication features
  [ ] M12. Testing and user feedback
          (emphasis on international, first-year, transfer, and first-generation
          students; WCAG-style accessibility review)
  [ ] M13. Pilot ahead of a career fair
  [ ] M14. Post-fair evaluation and lessons learned


## 9. GUARDRAILS (ACCURACY, PRIVACY, ACCESSIBILITY)
--------------------------------------------------------------------------------
Draft guardrails; to be confirmed with the Portfolio Vision Worksheet.

  - Accuracy: eligibility and employer information should be validated, and
    users should be told when information is unconfirmed or may be out of date.
  - Accessibility: venue accessibility information and an accessible interface
    are release requirements, not backlog items.
  - Privacy: student data should be handled with FERPA-aware practices, not
    sold or shared, and limited to what the features need.
  - Security: role-based access, least-privilege credentials, and encryption
    for stored and transmitted data.
  - Human accountability: employers own their listings; Career Services staff
    own the final review of employer registrations.
  - Fairness: international and first-generation students should receive
    clear, correct information, not assumptions.
  - Transparency: users should know when AI is generating plan suggestions.


## 10. INSTALLATION INSTRUCTIONS
--------------------------------------------------------------------------------
Detailed installation steps will be added as the project nears release.
In general, setup will involve obtaining the project source code, installing
the required dependencies, configuring environment settings and credentials
for any data services, and running the application locally or on a supported
device. Refer to this section for updates as development progresses.


## 11. TEAM MEMBERS AND DEVELOPERS
--------------------------------------------------------------------------------
  Tyson Watson - [Role]
  Richie Shadibaeva - [Role]
  Soleil Ector - [Role]
  Trevor VanderMolen - [Role]

Course: MIS 4000 Career Aid Project
Institution: Michigan Technological University


## 12. SUPPORTING PROJECT DOCUMENTS
--------------------------------------------------------------------------------
  - Career Aid Proposal (presentation: opportunity statement, competitors and
    niche, concept prototype)
  - Misc Notes 2026 (career fair observations and statistics)
  - MIS 4000 Career Aid Templates
  - Portfolio Vision Worksheet (template)

================================================================================
