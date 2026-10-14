# CarePath maternal continuity prototype

CarePath is a small, browser-only prototype for a maternal care continuity workflow across community and tertiary health facilities. It demonstrates a pregnancy journey, appointment reminders, referral follow-up, patient-controlled sharing choices, assisted access, and a low-bandwidth design.

## Run

Open `index.html` in a modern browser. There is no build step or backend.

## What this demonstrates

- A continuity view spanning registration, antenatal care, birth planning, and postnatal care.
- A next appointment and referral status that can be understood by a patient and a care team.
- Patient-facing sharing controls and a warning before a record is shared.
- A mobile-responsive interface with lightweight assets and no external services.

All patient information is fictional. Buttons demonstrate local UI behavior only; no clinical record is stored or transmitted. This prototype is not yet connected to SmartClinic, a live EMR, a messaging provider, or a health-information exchange. A production pilot requires clinical validation, privacy and security review, local approvals, user research, integration work, and a tested implementation plan.

## Open source status

This working prototype is intended to be released as a separate open-source component for the UNICEF Femtech Ventures application. It does not include Primed E-Health's proprietary SmartClinic Exchange or maternal-continuity production code. The public repository URL must be added after the repository is published.

## Safety and privacy

The demo uses no real patient data, makes no clinical recommendations, and does not transmit data. Sharing controls are illustrative only. Any pilot must define consent, access control, data minimization, retention, incident response, and clinical escalation with participating facilities.
