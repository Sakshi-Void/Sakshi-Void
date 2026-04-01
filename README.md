<!-- Profile README — Sakshi Singh | Cloud Security & IAM -->

<h1 align="center">Sakshi Singh</h1>

<p align="center">
  <b>Cloud Security · Identity & Access Management · Python Automation</b><br>
  <sub>Learning by building. Everything here is a work in progress.</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sakshi-singh-ds/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://tryhackme.com/p/SakshiVoid">
    <img src="https://img.shields.io/badge/TryHackMe-212C42?style=flat-square&logo=tryhackme&logoColor=white" />
  </a>
  <a href="mailto:singhsakshi0430@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</p>

---

## About

I'm shifting from web development into cloud security, with a specific focus on **Identity & Access Management (IAM)**.

My background is in Python and full-stack development (MERN/Next.js), but I've been spending most of my time lately on access control, IAM policy design, and cloud security fundamentals. I build small, hands-on projects to learn — not tutorials, actual scenarios with real configurations and writeups.

Right now I'm focused on:
- Writing and analyzing IAM policies on AWS (least privilege, permission boundaries, role assumptions)
- Azure Active Directory — RBAC, conditional access, service principals, MFA enforcement
- Python automation for IAM audits, credential reports, and security checks
- Reading CloudTrail logs to understand what happened and why

I'm based in Jharkhand, India. Still learning. Documenting everything.

---

## Current Focus Areas

| Area | What I'm working on |
|---|---|
| **AWS IAM** | Least-privilege policies, policy analysis, role trust relationships |
| **Azure AD / Entra ID** | RBAC assignment, conditional access policy design, MFA enforcement |
| **Python + boto3** | Automating IAM audits, parsing CloudTrail logs, credential report analysis |
| **CSPM Concepts** | Understanding misconfigurations, remediation workflows |
| **Compliance** | CIS AWS Benchmark — IAM controls section |

---

## Projects (Cloud Security)

> Each repo has a real-world scenario, the actual config files/scripts, and a writeup of what I learned.

| # | Project | What it does | Stack |
|---|---|---|---|
| 01 | [aws-iam-policy-lab](https://github.com/Sakshi-Void/aws-iam-policy-lab) | Least-privilege IAM policy setup from scratch — simulates a real over-permissioned developer scenario | AWS IAM, JSON |
| 02 | [iam-policy-analyzer](https://github.com/Sakshi-Void/iam-policy-analyzer) | Python script that parses IAM policy JSON and flags overly permissive rules (wildcards, */*) | Python |
| 03 | [cloudtrail-log-parser](https://github.com/Sakshi-Void/cloudtrail-log-parser) | Parses CloudTrail logs to surface suspicious API calls and unusual access patterns | Python, AWS CloudTrail |
| 04 | [s3-misconfiguration-lab](https://github.com/Sakshi-Void/s3-misconfiguration-lab) | Intentional S3 misconfiguration → detection → Python-based remediation | AWS S3, IAM, Python boto3 |
| 05 | [service-account-auditor](https://github.com/Sakshi-Void/service-account-auditor) | Identifies IAM roles and access keys unused for 90+ days using AWS Credential Reports | Python, boto3 |
| 06 | [azure-ad-access-lab](https://github.com/Sakshi-Void/azure-ad-access-lab) | Azure AD user/group setup, RBAC role assignment, and MFA enforcement for a simulated org | Azure AD, Entra ID |

*More being added as I build. Links go live when the repo is ready.*

---

## Tools & Platforms

**Cloud**
`AWS IAM` `AWS CloudTrail` `AWS S3` `Azure Active Directory` `Microsoft Entra ID` `AWS Config`

**Languages & Scripting**
`Python` `boto3` `JSON` `Bash (basics)`

**Security Concepts**
`RBAC` `ABAC` `Least Privilege` `Permission Boundaries` `Service Principals` `Zero Trust` `CSPM` `MFA Enforcement` `Access Review` `CIS Benchmarks`

**Other**
`TryHackMe (Blue Team rooms)` `Linux` `Git`

---

## Currently Studying

- **AWS Solutions Architect Associate** — building cloud foundations alongside security
- **CompTIA Security+** — in progress
- **Microsoft SC-900** — next on the list
- TryHackMe rooms focused on cloud and IAM scenarios

---

## A Note on the Other Repos

You'll see a few web development projects here (Python chatbots, MERN projects). Those are from before I shifted focus — keeping them because they show how I think and write code, not because they're relevant to IAM.

The cloud security repos are what I'm actively building and maintaining.

---

<sub>📍 Jharkhand, India &nbsp;·&nbsp; Open to cloud security internships and junior IAM roles &nbsp;·&nbsp; singhsakshi0430@gmail.com</sub>
