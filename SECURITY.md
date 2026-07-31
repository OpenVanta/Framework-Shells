# Security Policy

Framework Shells is a documentation repository: it contains framework/control
CSVs and README files that customers import into Vanta as Custom Frameworks.
It contains no application code, no customer data, and nothing that runs or
executes. 

## Reporting a security concern

If you believe a file in this repository has been tampered with, contains
unauthorized or sensitive data, or could cause an import into Vanta to behave
unexpectedly, please do not open a public issue.

Report it via GitHub's "Report a vulnerability" button on this repository's
Security tab, or email security@vanta.com.

Please include:

- Which file(s) are affected.
- What you expected vs. what you found.
- The commit or version you reviewed.

## Scope notes

- Shells are static reference content no
  pre-mapped evidence.
- Importing a shell is a manual, customer-initiated action inside the Vanta
  UI; this repository does not perform imports or connect to Vanta itself.
- Content accuracy issues (e.g. a control mapping that looks wrong) are not
  security vulnerabilities — please raise those as a normal issue or through
  your Vanta Customer Success Manager instead.
