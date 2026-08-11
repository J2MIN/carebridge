# CareBridge

**Community care, connected.**

CareBridge is an interactive prototype of an AI-assisted prioritization system for ward- and commune-level health workers. It demonstrates how fragmented patient records, appointment history, and vital signs can be turned into a clear daily worklist—while keeping the final care decision with the health worker.

### [Open the live demo](https://j2min.github.io/carebridge/)

![CareBridge dashboard preview](https://j2min.github.io/carebridge/og.jpg)

## The problem

Primary care teams often manage large numbers of patients with hypertension, diabetes, and other chronic conditions. When records are reviewed manually, missed appointments, worsening measurements, and unconfirmed medication use can be discovered too late.

CareBridge explores a more proactive workflow:

```text
Patient data → Risk signals → Priority list with reasons → Human action
```

## What the prototype demonstrates

- **Daily priority queue** sorted by urgency and intervention potential
- **Explainable risk view** with priority score, vital-sign trends, and alert reasons
- **Care action recording** for patient calls, medication reminders, and appointment rescheduling
- **Follow-up workflow** separated into pending, scheduled, and completed work
- **Activity reporting** with response and intervention summaries
- **Vietnamese and Korean interfaces** for a Vietnam–South Korea project team
- **Human-in-the-loop design** that supports, rather than replaces, health workers

## Demo flow

1. Open the highest-priority patient.
2. Review the blood-pressure or glucose trend and the reasons for prioritization.
3. Record a call, medication reminder, or appointment change.
4. Check the updated follow-up board and activity report.

Changes made during the demo are stored in the current browser and can be reset from **Settings**.

## Prototype scope

This website is a functional workflow prototype, not a production clinical system.

- All patient information is fictional.
- Risk scores and reporting data are simulated for demonstration.
- The current version does not connect to electronic medical records or run a validated predictive model.
- It must not be used with real patient data or for clinical decision-making.

A production version would require secure shared storage, authentication and access control, audit logs, health-data integration, model validation, and local clinical governance.

## Technology

- React 19
- TypeScript
- Vite
- Responsive web interface
- GitHub Pages

## Project goal

CareBridge aims to help community health teams move from reactive record review to proactive, explainable, and coordinated chronic-care follow-up.

---

Developed as a community-health technology prototype for demonstration and research.
