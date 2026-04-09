# Public Demo: Order Document Automation

This folder presents a safe, public showcase of a Google Workspace automation system that generates invoice and report packages from one operational source.

It is written for business and technical readers who need to understand what the system does, how it is used, and why it is operationally useful.

## Key Capabilities

- Supports two billing models in one flow: TM (hour-based) and FP (fixed monthly with overtime logic)
- Generates multi-document output in one run: gDoc, PDF, and signed PDF
- Applies server-side recalculation before output to reduce total mismatches
- Preserves run traceability with logging and repeatable generation flow
- Uses additive, non-destructive output handling with clear artifact organization

## Outcome Snapshot

- Preparation time reduced from about 2 working days to about 10 minutes
- Manual document assembly risk reduced through deterministic generation
- Operational handoffs reduced for routine billing closure

## Demo Access

- Demo Viewer: https://docs.google.com/spreadsheets/d/1JUpzYpNbTBxQrUdxjW2XcXKGB2t9WTbv9pg12wPPLjg/edit?usp=sharing
- Deployed Application: https://script.google.com/macros/s/AKfycbx2oa6XNMUjDHL7GLhG693FovAVhuLafTBeWe8G9y7H5uFZLFioAqAMAqUCO0-ndvBg/exec
- Public Showcase Repository: https://github.com/keindabest/sc-demo-invoice-report-creator-showcase

## Quick How to Try Demo

1. Open the deployed application.
2. Load available order data from the connected container.
3. Select an order and configure report blocks.
4. Choose output types (gDoc, PDF, signed PDF).
5. Run generation and review produced artifacts.

## Demo Documentation Map

- [OVERVIEW.md](OVERVIEW.md)
- [ARCHITECTURE.md](ARCHITECTURE.md)
- [DEMO_FLOW.md](DEMO_FLOW.md)
- [FEATURES.md](FEATURES.md)
- [USE_CASES.md](USE_CASES.md)
- [SECURITY_AND_DISCLOSURE.md](SECURITY_AND_DISCLOSURE.md)
- [DEPLOYMENT.md](DEPLOYMENT.md)
- [ARTIFACTS.md](ARTIFACTS.md)
- [LICENSE](LICENSE)

## Disclosure (Short)

This is a sanitized public demo package. Production-specific orchestration details, sensitive naming patterns, and client-specific implementation workflows are intentionally excluded.

## License

This project is licensed under the MIT License. See LICENSE.

## Author

Daniel Kein
https://www.linkedin.com/in/daniel-kein/
