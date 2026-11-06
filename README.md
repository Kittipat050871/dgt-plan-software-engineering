# DGT Plan | Software Engineering Project

**Student scheduling, course exploration, and campus activity management**  
Academic group project - 1101163 Project in Software Engineering, Suranaree University of Technology (SUT)

## Overview

DGT Plan is a mobile application project designed to help students organize academic schedules, explore course/career information, manage personal activities, and see announcements from academic staff. The project includes student-facing and administrator/staff-facing flows.

This repository showcases the **software engineering process and system analysis artifacts**, rather than claiming to distribute production-ready application source code. It is based on the group's project documentation and test records.

## My contribution

**Role: System Analyst** (five-member academic team)

- Participated in requirements and workflow analysis for student and staff use cases.
- Supported the documentation and traceability of system requirements.
- Worked with the team's analysis/design and validation documentation, including SRS, RTM, SIT, and UAT artifacts.

The application was a collaborative class project; this repository does not claim sole authorship of the software or other teammates' work.

## Technology documented for the application

| Area | Technology |
| --- | --- |
| Mobile application | Expo, React Native |
| Languages | TypeScript / JavaScript |
| Navigation | Expo Router |
| Authentication | Firebase Authentication |
| Data storage | Firebase Firestore |
| Testing & analysis | SRS, requirements traceability, SIT, UAT |

## Functional scope

- Student registration, sign-in, password reset, and role-based navigation.
- Course and career information for student planning.
- Academic and personal activity scheduling.
- Department announcements and student-facing event information.
- Event/reminder and notification-related workflows.
- Staff/admin workflows for publishing and managing announcements.

These are features described in the team's documents; not every behavior has been independently re-tested for this portfolio.

## Engineering evidence

| Artifact | Evidence documented |
| --- | --- |
| Software Requirements Specification (SRS) | Product scope, use cases, process/data-flow diagrams, feature requirements, quality attributes |
| Requirements Traceability Matrix (RTM) | 14 requirement entries (RQ-001 through RQ-014) recorded as Done |
| System Integration Testing (SIT) | 13 recorded scenarios (SIT-001 through SIT-013), all marked Pass |
| User Acceptance Testing (UAT) | 14 recorded scenarios (UAT-001 through UAT-014), all marked Pass |

**Evidence disclaimer:** Results above summarize the academic team's existing records. They are *not* a fresh independent test, production certification, or security audit. See [Testing Summary](docs/Testing_Summary.md).

## Documents in this repository

- [System Analysis Case Study (PDF)](docs/DGT_Plan_System_Analysis_Case_Study.pdf)
- [Testing Evidence Summary](docs/Testing_Summary.md)
- [Repository Release Checklist](docs/Publication_Checklist.md)

## Source code, APK, and demo access

The original team project includes an Android APK and related material. **Neither the APK nor the application source code is distributed here** because they have not yet undergone an independent review for embedded credentials, cloud configuration, user records, and redistribution permissions. No public demo login is provided.

If a sanitized and authorized source release becomes available, it can be added in a separate, reviewed commit.

## Academic and ethical notice

- University coursework, not an official SUT application or service.
- This is an educational prototype, not a production-deployed system.
- Credentials, personally identifiable student/team information, and unreviewed team materials are intentionally excluded.
- No license is asserted for third-party or team-owned artifacts.
