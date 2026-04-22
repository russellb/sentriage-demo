# Sentriage Demo

A public demo of [Sentriage](https://github.com/russellb/sentriage) —
AI-powered triage for security vulnerability reports.

This repo is a sentriage instance monitoring
[russellb/vulnerable-demo-project](https://github.com/russellb/vulnerable-demo-project),
a small Flask app with intentional vulnerabilities.

## What to look at

Browse the [Issues](../../issues) to see how sentriage processes
vulnerability reports:

1. **Valid vulnerability** — SQL injection correctly identified and assessed
2. **Duplicate report** — second report of the same vulnerability caught by duplicate detection
3. **Invalid report** — report claiming a vulnerability that doesn't exist, correctly rejected
