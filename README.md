# DREAMLEAP GYMSTARS V2 — Full UI Migration

A modular, flat-file HTML/CSS/JavaScript recreation of the original GymStars Phase 1 demo.

All files are at repository root for straightforward iPad uploads. Main areas include Coach/Admin, Family Space, Parent View and Kids Mode. Demo state is saved in localStorage using the original key `dreamleap-gymstars-demo-v1`.

This remains a front-end demo. It does not provide real authentication, server-side permissions, secure multi-device data sync, or production push notifications. Do not enter real student data.


## V2 update: Skill Assessment & Stars
- Coach can record a named skill assessment for an individual student.
- Assessment outcomes: First Attempt, Improving, Mastered.
- Star rules are editable in Coach > Progress.
- Coach Bonus Stars are separate and require a reason.
- Assessment history and Star Points transactions are stored locally.
- Family > Skills shows the selected child's assessment history.
- Family > Rewards shows active rewards and points remaining to each reward.
- Existing local demo data is retained when upgrading; new fields are initialized automatically.
- This remains a local demo prototype. Server-side permissions, secure multi-device sync, push notifications, and real redemption workflows are not yet implemented.
