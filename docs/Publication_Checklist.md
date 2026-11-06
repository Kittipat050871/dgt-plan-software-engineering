# DGT Plan - Publication Checklist

Before making this repository public or adding a source-code/APK release:

- [ ] Obtain the team's permission to republish shared code, images, diagrams, or project documents.
- [ ] Remove account emails, demonstration passwords, authentication tokens, and private Firebase configuration from published docs and scripts.
- [ ] Rotate any credentials exposed in the original README or other distributed documents; assume they may have been copied already.
- [ ] Review Firebase Security Rules and verify student/admin authorization against unauthorized reads and writes.
- [ ] Remove student IDs, phone numbers, personal emails, team member contacts, and real user/sample records.
- [ ] Confirm no private keys, service-account JSON, `.env` values, or identifiable analytics records are in version history.
- [ ] Confirm the APK is safe to distribute and contains no embedded private credentials; do not rely on ZIP/.gitignore to hide secrets after a commit.
- [ ] Attribute the group project and differentiate System Analyst responsibilities from software implementation.
- [ ] Re-run app and functional tests and update README claims before distributing a runnable build.

**Current publication scope:** README + newly authored case study + non-sensitive test summary only; source and APK are intentionally excluded.
