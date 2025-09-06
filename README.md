# open-source-contribution-week2

Open-source contribution to **Day 41 – Compliance & Governance** in the Architecture_Journey project.  
This work introduces a Python scaffold for HIPAA compliance checks on AWS (S3 security, CloudTrail logging) and provides documentation to highlight governance and GRC skills in a practical, industry-relevant project.

---

## Links
- Pull Request: [PR #175 – feat(day41): add starter AWS HIPAA compliance checks (S3 + CloudTrail)](https://github.com/saravanakumarrc/Architecture_Journey/pull/175)  
- Upstream Issue: [Day 41 – Implement Compliance & Governance Frameworks (#145)](https://github.com/saravanakumarrc/Architecture_Journey/issues/145)  
- My Fork: [rdlasco/Architecture_Journey](https://github.com/rdlasco/Architecture_Journey)

---

## What I Contributed
- `compliance/day41/README.md` → scaffold README for compliance checks  
- `compliance/day41/s3_public_access_check.py` → starter Python script (placeholder for HIPAA checks)  

---

## Why This Matters
- Provides a practical starting point for HIPAA governance checks on AWS.  
- Aligns with compliance frameworks (HIPAA, SOC2) and upstream acceptance criteria.  
- Demonstrates cloud security automation skills relevant to coursework and real-world GRC roles.  

---

## Requirements Models

**User Story**  
As a cloud compliance engineer, I want to run a script that validates AWS governance settings so that I can ensure HIPAA alignment before audits.  

**Use Case**  
1. Contributor runs the Python script.  
2. Script checks AWS guardrails (S3 public access, S3 encryption, CloudTrail logging).  
3. Contributor uses the results as evidence for governance reporting.  

---

## Next Steps
- Replace the placeholder `print()` with real `boto3` AWS compliance checks.  
- Expand README with mappings to HIPAA and SOC2 controls.  
- Add screenshots and sample outputs as evidence of testing.  
