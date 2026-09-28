# Security Risk Assessment & Prioritization

## What this repository demonstrates

This repository is intended to show the ability to move from **asset/threat identification** to **risk quantification, prioritization, control selection, and residual-risk reasoning**.

### Historical evidence
A prior information-security assignment (Nov. 2024) involved:
- Annual Rate of Occurrence (ARO)
- Single Loss Expectancy / Annualized Loss Expectancy reasoning
- post-control risk estimation
- control cost-benefit analysis
- a final control adoption decision

A later NIST-oriented assignment (Dec. 2024) involved a CSF/profile spreadsheet with likelihood, impact, and calculated risk scores.

The original numeric artifacts are not included here unless independently recovered and verified.

## Public portfolio reconstruction

Use a **synthetic company and synthetic values** to demonstrate the method without misrepresenting the original graded assignment.

### Core formulas

- `SLE = Asset Value × Exposure Factor`
- `ALE = SLE × ARO`
- `Annualized Risk Reduction = ALE_before − ALE_after`
- `Net Control Benefit = Annualized Risk Reduction − Annualized Control Cost`

### Suggested workflow
1. Identify assets and business dependencies.
2. Identify threats and vulnerabilities.
3. Estimate likelihood/ARO and impact.
4. Calculate inherent risk.
5. Rank risks against stated risk appetite.
6. Select treatment: mitigate, transfer, avoid, or accept.
7. Estimate control effectiveness and residual risk.
8. Compare annualized risk reduction with control cost.
9. Document assumptions and uncertainty.

## Interview framing

> I have completed structured security-risk work that required me to identify and score risks, prioritize remediation, evaluate mitigation choices, and compare post-control risk with cost. I separate the underlying calculation from the management decision so assumptions can be challenged.
