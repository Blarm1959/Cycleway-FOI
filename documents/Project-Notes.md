# Cycleway-FOI project notes

## Purpose

Maintain the information request and evidence concerning costs, programme, traffic restrictions, heritage issues and funding risks for the Hexham to Corbridge Active Travel Corridor.

## Initial document set

- `documents/FOI-EIR-Request.md`: latest checked request from the chat, ready for sender details and submission.
- `documents/Fact-Check-and-Sources.md`: supporting findings, public source links and unresolved questions.
- `documents/Project-Notes.md`: purpose, document map and workflow.

The superseded Claude draft is not the current request. Confirmed facts and unverified claims are separated in the fact-check document. No submission or council response is recorded yet.

## PSTP workflow

Download `Cycleway-FOI-Changes-v1.0.1.zip` to Downloads. From the local Cycleway-FOI repository in PowerShell 7, run:

```powershell
.\PSTP.ps1 Release -Zip
```

The ZIP contains new documents at repository-relative paths, without an enclosing project folder. PSTP owns release metadata and version changes. The package does not include `release.json`, `build-info.json`, `README.md`, the launcher or the bootstrap rules.
