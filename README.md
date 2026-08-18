# ISOC trainer database

Sole canon for ISOC trainer records and photos. Established 18 August 2026, migrated from Trainer_bios_2026_v2.docx merged with the Trainers tab of the ISOC core database.

## Structure

One folder per trainer under `trainers/`, named by trainer code:

- `record.json` — code, name, title, status, categories, languages, the three bio tiers (bio_short, bio, bio_long), the fuller bio as a list of paragraphs (bio_full) and photo provenance
- `photo.jpg` — 600 x 600 headshot

## Rules

- Nothing internal-only (rates, contact details, notes) ever enters this repo.
- The Trainers tab of the ISOC core database is a generated mirror of this repo. After any write here, regenerate the tab CSV and paste it into the Sheet — the tab still drives the website trainers page.
- The Word master (Trainer_bios format) is generated output, regenerated on demand.
- Photo quality shortfalls are tracked in `photo-debt.md`.

Maintained through the isoc-trainer-bios Claude skill.
