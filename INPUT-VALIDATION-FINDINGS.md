# Input-Validation Findings

Name: Amansanba
Date: 3 November 2026

| # | File and line | Issue | How it was found | Fix applied | Retest result |
| --- | --- | --- | --- | --- | --- |
| 1 | app.js, /user route | SQL injection | Snyk Code (SAST) | Allow-list validation and parameterised query | Attack URL now returns Invalid name |
| 2 | app.js, /search route | Reflected XSS | Snyk Code | Not fixed yet, planned for Wednesday | - |

## What I noticed comparing Snyk Code and SonarQube for IDE

Write one or two sentences here.
- In the api.js, SonarQube gave the problems it found in package.json and api.js and underlined the data types.
- Snyk gives the number of severity whether critical, high, medium and low