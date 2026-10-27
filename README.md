# SAKHI — A Patient-Controlled Rural Health Passport

**Team:** SakhiTech  
**Problem Statement ID:** SIH26129  
**Theme:** Miscellaneous  
**Category:** Software

## Overview
SAKHI is a proposed patient-controlled rural healthcare passport designed to connect fragmented healthcare services through secure, standardised, consent-based information exchange. Healthcare is the initial interoperability use case.

## Problem
Rural healthcare journeys can involve scattered information, repeated data entry, disconnected referrals, different data formats, limited visibility, and unreliable internet connectivity.

## Proposed Features
- QR-based patient linking. The QR code links to authorised information; patient records are not stored inside the QR code.
- Consent-based access to authorised healthcare information.
- Multilingual voice assistance to help people navigate the service.
- Patient timeline and structured referral information.
- Offline-first data entry with synchronisation when internet access returns.
- Modular connectors and APIs for participating systems.
- Authentication, role-based access control, encryption, and audit logs.

## Intended Users
- Rural patients and families
- ASHA workers
- Healthcare professionals and participating facilities

## Technical Concept
1. A user links to a patient record using a QR code.
2. The system authenticates the user and checks consent and access permissions.
3. A SAKHI interoperability layer validates and transforms information into a common data model.
4. Authorised information can be exchanged with participating systems through APIs.
5. When offline, permitted entries are saved locally and synchronised when connectivity is available.

## Prototype Scope
This repository is a student demonstration website. It uses illustrative information only and does not connect to real healthcare systems or store real patient records. Any integration with official platforms would require authorised API access, applicable standards, permissions, and security review.

## Project Files
- `index.html` — website content
- `style.css` — website styling
- `README.md` — project documentation

## Future Roadmap
1. Controlled prototype using simulated data and APIs.
2. Demonstrate ASHA workflow, referral, offline entry, and synchronisation.
3. Pilot with participating healthcare facilities and authorised systems.

## Important Privacy Note
Do not upload real patient data, personal medical records, passwords, API keys, or other sensitive information to this repository.
