# Industrial Automation Engineering Casebook

Open field references, checklists, lightweight tools and reusable data templates for engineers maintaining or migrating legacy industrial control systems.

This repository is maintained by **PLCProTech Ltd.** and is intended to be useful on its own. It is not a collection of product advertisements or invented customer stories.

## Current cases

1. **Legacy PLC Replacement Planning** — recovery-risk assessment, migration sequence and survey template.
2. **DCS Spare Module Failure Planning** — critical-spares scoring based on process impact, redundancy, lead time and recovery options.
3. **Bently Nevada 3500 Rack Spare Strategy** — rack survey, redundancy review and critical-spare planning using current Baker Hughes documentation.
4. **PLC Power Supply Failure Troubleshooting** — structured fault-isolation sequence and downloadable checklist.
5. **Document a Legacy Control System Before Migration** — browser-based survey form with JSON export and CSV field sheet.

## Reusable data

The `data/` directory contains plain CSV worksheets that can be opened in Excel, LibreOffice, Google Sheets, Python or any text editor.

## Engineering rules used in this project

- Record exact installed catalog numbers instead of guessing from product families.
- Treat firmware, hardware revision and rear I/O assemblies as compatibility evidence where applicable.
- Separate verified facts from planning assumptions.
- Prefer current manufacturer manuals and datasheets for platform-specific statements.
- Do not present a generic scenario as a real customer case.
- Do not bypass site safety, change-control or manufacturer procedures.

## Sources

Platform-specific 3500 information in Case 03 is based on current public Baker Hughes / Bently Nevada 3500 system documentation, including the 3500 System Datasheet and product resource pages.

- https://www.bakerhughes.com/bently-nevada/monitoring-systems/machinery-protection/3500-machinery-protection-systems
- https://dam.bakerhughes.com/m/3e2d1931acef5630/original/3500-System-Datasheet-162096-pdf.pdf

## Maintainer

Maintained by [PLCProTech Ltd.](https://www.plcprotech.com/pages/about-us).

Additional industrial automation technical articles are available in the [PLCProTech Knowledge Center](https://www.plcprotech.com/blogs/knowledge).

## Maintenance policy

Updates are made when they add practical engineering value: new field tools, corrected technical information, improved checklists, reusable datasets, manufacturer-source updates or clearer recovery workflows. The project is not updated merely to create commit activity.
