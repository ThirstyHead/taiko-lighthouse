# Lighthouse from the CLI

Notes on running Lighthouse from the command line.

## Installation

`npm install -g lighthouse`

## Default Behavior

Test a website, saves HTML report to current directory.

`lighthouse https://www.thoughtworks.com/`

Test a website, save HTML, JSON, and CSV reports

`lighthouse https://www.thoughtworks.com/ --output=json,html,csv`

Only run Accessibility audits

`lighthouse https://www.thoughtworks.com/ --output=json,html,csv --only-categories=accessibility`
