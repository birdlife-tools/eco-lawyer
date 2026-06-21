# Eco-Lawyer

Generate formal legal complaints from field worker descriptions.

## Problem

When ecologists find violations in the field (poisoning, nets, illegal construction), they must write formal complaints to inspections using strict legal language and citing exact law articles, otherwise complaints are rejected. Writing these takes hours.

## Solution

Local application with structured law database that takes plain field worker description ("We found bird nets at location X") and automatically generates formal legal document (PDF) ready for signature and submission.

## Technical Stack

- Local RAG (Retrieval-Augmented Generation) system with ecological and criminal law database
- Automatic legal template population
- PDF generation via `ReportLab`
- Designed for localization — law databases can be swapped per country/jurisdiction

## Status

🚧 Planning

## Community

Join the discussion:

[![Matrix](https://img.shields.io/badge/Matrix-Chat-black?logo=matrix)](https://matrix.to/#/#eco-lawyer:matrix.org)

## License

MIT — see [LICENSE](LICENSE)
