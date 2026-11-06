# DGT Plan - Testing Evidence Summary

This summary is reconstructed from the academic group's RTM, SIT, and UAT files. The original worksheets are not distributed because they may include names, internal notes, or other information requiring review.

## Requirements traceability

- The team's RTM lists **14** requirement entries, `RQ-001` through `RQ-014`.
- All 14 entries were recorded as **Done** in the supplied matrix.
- Covered areas include authentication, password recovery, course/career information, activity scheduling, notifications, staff login, and announcements.

## System integration testing (SIT)

- **13** documented scenarios: `SIT-001` to `SIT-013`.
- The original worksheet marks **13 Pass, 0 Fail**.
- Examples of tested flows: successful/unsuccessful login, password recovery, retrieval of course/career data, activity schedule display, and notifications.

## User acceptance testing (UAT)

- **14** documented cases: `UAT-001` to `UAT-014`.
- The original worksheet marks **14 Pass, 0 Fail**.
- Examples include account registration, login, error messaging, password reset, reading career guidance, activity schedules, and staff announcements.

## Interpretation and limits

These are **reported outcomes in team-maintained academic documents**. This portfolio did not rerun tests or independently verify the underlying app/build, coverage completeness, device compatibility, security controls, performance, notification delivery, or live cloud environment. `Done` in the RTM is a documented status, not proof of production readiness.

Before a public APK/source release, repeat authentication/authorization, data access, privacy, and functional tests using test-only users and a non-production Firebase project.
