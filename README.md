# Health Care Domain — Learning Repository

A self-contained study resource for professionals entering the healthcare IT space — no clinical background required.

---

## What this is

Healthcare and medical imaging come with a dense vocabulary: PACS, DICOM, HL7, FHIR, IHE profiles, modality codes, workflow roles, and regulatory acronyms that insiders use without thinking. This repository makes that language accessible to software engineers, QA engineers, product managers, and anyone else joining the healthcare domain from outside.

The current resource is **Imaging Lexicon** — an interactive, browser-based study console covering clinical imaging and Health IT terminology.

---

## Imaging Lexicon (`imaging-lexicon.html`)

Open the file directly in any modern browser. No server, no install, no dependencies.

### What's inside

| Module | What you'll learn |
|---|---|
| **Modalities** | CT, MRI, Ultrasound, Mammography, PET, Nuclear Medicine, and the two-letter DICOM codes for each |
| **Core Systems** | PACS, RIS, HIS, EHR, VNA, CVIS — what each system does and how they connect |
| **DICOM** | The imaging file format and network protocol: tags, UIDs, SOP classes, transfer syntax, and the C-STORE / C-FIND / C-MOVE / C-ECHO verbs |
| **Interoperability** | HL7 v2 messages (ADT, ORM, ORU), FHIR, IHE profiles (SWF, XDS-I, PIX/PDQ) |
| **Workflow & Roles** | Order to report: accession numbers, the technologist, the radiologist, priors, report status, STAT priorities |
| **Cardiology Imaging** | Echo, cath lab, ECG waveforms, CVIS, FFR, ejection fraction — cardiovascular data flows |
| **Radiology Practice** | Contrast, dose reports, teleradiology, BI-RADS, peer review, structured reporting |
| **PACS Operations** | Auto-routing, prefetching, tag morphing, tiered storage, data migration, compression |
| **Healthcare & Regulatory** | HIPAA, PHI, FDA device regulation, IEC 62304, CPT/ICD-10 coding, audit trails |
| **QA & Testing** | Verification vs Validation, conformance testing, interface testing, round-trip testing, traceability |

### Study modes

- **Overview** — all modules at a glance with your progress
- **Flashcards** — flip cards with abbreviation on the front and definition on the back; mark what you know
- **Glossary** — full searchable reference, filterable by module
- **Quiz** — 10 multiple-choice questions drawn from the full lexicon
- **Learning Paths** — guided routes through the material in a logical order
- **Journeys** — story-based walkthroughs following imaginary patients through real clinical workflows, touching every term in context

Progress (cards marked as known) is saved in your browser's local storage.

---

## Who this is for

- Software / QA engineers joining an enterprise imaging or health IT team
- Product managers and business analysts working on PACS, RIS, EHR, or interoperability projects
- Anyone preparing for a healthcare IT role who needs terminology fluency fast

---

## How to use it

```bash
# Clone the repo
git clone https://github.com/ankitrathi85/health-care-domain.git

# Open the file in your browser
open health-care-domain/imaging-lexicon.html
```

No build step. Everything runs locally in the browser.

---

## Contributing

Corrections, new terms, and additional modules are welcome. Open a pull request with your changes to `imaging-lexicon.html`.
