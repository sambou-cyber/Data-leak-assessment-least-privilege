# Data Leak Assessment, Least Privilege Review

## Overview
This repository documents an internal review of a data leak incident
caused by improper enforcement of the principle of least privilege. The
assessment evaluates contributing factors, reviews existing access
controls, and recommends improvements aligned with NIST SP 800-53 AC-6.

## Objective
- Analyze factors that led to a data leak
- Review least privilege controls
- Identify control enhancements
- Improve information privacy and data handling practices

## Incident Summary
An internal folder containing confidential business documents was shared
with a sales team during a meeting. Access to the folder was not revoked
afterward. During a sales call, an employee accidentally shared the
entire folder with an external business partner, who later posted the
link publicly on social media.

## Control Review
The assessment focuses on the principle of least privilege as defined in
NIST SP 800-53 AC-6, which requires users to have only the minimum access
necessary to perform their job functions.

## Recommendations
- Automatically revoke access to shared folders after a defined time
  period.
- Restrict access to sensitive internal folders based on user roles and
  limit external sharing to approved files only.

## Outcome
Implementing these control enhancements reduces the likelihood of
accidental data exposure by limiting access scope and duration, helping
the organization better protect sensitive information.

---

Prepared by: Sambou Kamissoko  
LinkedIn: https://www.linkedin.com/in/sambouk/
