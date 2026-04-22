# Invoice&Report Creator for selected Client

This public demo shows a Google Workspace automation flow that turns recurring billing input into ready invoice and report packages in one run.

For teams closing routine contractor billing, it replaces fragmented manual assembly with a guided and traceable process.

Typical preparation time moves from about 2 working days to about 10 minutes.

![Invoice Report Creator demo hero](assets/screenshots/hero_section.png)

## Key Capabilities

- Handles both billing models in one process: TM (hour-based) and FP (fixed monthly with overtime logic)
- Generates complete document outputs in one run: gDoc, PDF, and signed PDF
- Recalculates totals server-side before output so generated totals match validated inputs
- Keeps each run traceable with logging and repeatable generation steps
- Preserves prior artifacts during reruns with non-destructive output handling

## Outcome Snapshot

<table width="100%">
  <colgroup>
    <col width="40%" />
    <col width="30%" />
    <col width="30%" />
  </colgroup>
  <thead>
    <tr>
      <th align="left">Dimension</th>
      <th align="left">Before</th>
      <th align="left">After</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Preparation time</td>
      <td>About 2 working days</td>
      <td>About 10 minutes</td>
    </tr>
    <tr>
      <td>Document assembly risk</td>
      <td>Manual multi-step assembly</td>
      <td>Deterministic generation in one run</td>
    </tr>
    <tr>
      <td>Operational handoffs</td>
      <td>Multiple routine handoffs</td>
      <td>Reduced handoffs for billing closure</td>
    </tr>
  </tbody>
</table>

## Demo Access

<table width="100%">
  <thead>
    <tr>
      <th align="left" width="36%">Resource</th>
      <th align="left">Link</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Web Application</td>
      <td><a href="https://script.google.com/macros/s/AKfycbx2oa6XNMUjDHL7GLhG693FovAVhuLafTBeWe8G9y7H5uFZLFioAqAMAqUCO0-ndvBg/exec">Open Web Application</a></td>
    </tr>
    <tr>
      <td>Data Source (Google Sheets)</td>
      <td><a href="https://docs.google.com/spreadsheets/d/1JUpzYpNbTBxQrUdxjW2XcXKGB2t9WTbv9pg12wPPLjg/edit?usp=sharing">Open Data Source</a></td>
    </tr>
    <tr>
      <td>Generated Output Folder (Google Drive)</td>
      <td><a href="https://drive.google.com/drive/folders/1T7l4R3PMPFFR2-jJxzz9QeDYiwZDUg5h">Open Output Folder</a></td>
    </tr>
    <tr>
      <td>Public Showcase Repository</td>
      <td><a href="https://github.com/keindabest/sc-demo-invoice-report-creator-showcase">Open public showcase repository</a></td>
    </tr>
  </tbody>
</table>

## Quick How to Try Demo

1. Open the deployed application.
2. Load available order data from the connected container.
3. Select an order and configure report blocks.
4. Choose output types (gDoc, PDF, signed PDF).
5. Run generation and review produced files.

## Demo Documentation Map

- Start here: [OVERVIEW](OVERVIEW.md) -> [DEMO_FLOW](DEMO_FLOW.md) -> [FILES](FILES.md)
- [FEATURES](FEATURES.md)
- [ARCHITECTURE](ARCHITECTURE.md)
- [USE_CASES](USE_CASES.md)
- [SECURITY_AND_DISCLOSURE](SECURITY_AND_DISCLOSURE.md)
- [DEPLOYMENT](DEPLOYMENT.md)
- [LICENSE](LICENSE)

## Disclosure (Short)

This is a sanitized public demo package. Production-specific orchestration details, sensitive naming patterns, and client-specific implementation workflows are intentionally excluded.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).

## Author

Daniel Kein

https://www.linkedin.com/in/daniel-kein/
