# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| latest  | :white_check_mark: |
| < latest| :x:                |

## Reporting a Vulnerability

We take security seriously at Rustchain. If you discover a security vulnerability, please follow responsible disclosure. 

### How to Report

1. **DO NOT** open a public GitHub issue for security vulnerabilities.
2. **Primary Method:** Submit your findings using GitHub's [Private Vulnerability Reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) feature on this repository.
3. **Alternative Method:** Email your report directly to `[Insert Security Email, e.g., security@rustchain.com]`. *(Optional: Add PGP key info here if you have one).*
4. **Coordination:** You may reach out on [Discord](https://discord.gg/VqVVS2CW9Q) via DM to a maintainer to notify us that a report has been submitted, but **do not share exploit details over Discord**.

### What to Include

- Description of the vulnerability and its potential impact.
- Step-by-step instructions to reproduce the issue.
- Proof of Concept (PoC) code or scripts.
- Suggested fix or mitigation (if any).

### What to Expect

- **Acknowledgment:** Within 48 hours of your report.
- **Initial Assessment:** Within 1 week.
- **Resolution Timeline:** Communicated after the initial assessment.
- **Credit:** Included in the security advisory (unless you prefer to remain anonymous).

## Bounty Rewards

Security-related contributions are eligible for RTC token rewards based on the severity of the vulnerability. Severity is determined at the sole discretion of the Rustchain maintainers based on the CVSS score and actual impact.

| Severity | Reward (in RTC) | Examples |
| -------- | --------------- | -------- |
| Critical | 100-150 RTC     | Consensus failure, unauthorized minting, funds at risk |
| High     | 75-100 RTC      | Data leak, auth bypass, severe bridge logic flaw |
| Medium   | 20-50 RTC       | Targeted DoS, exploitable logic errors |
| Low      | 1-10 RTC        | Info disclosure, significant deviation from best practice |

*Note: Bounties are paid out in RTC tokens. [Optional: Add a note here if KYC is required to claim payouts, or if there is a vesting schedule].*

### Scope

The following are in scope for security reports:

- Consensus mechanism vulnerabilities.
- Proof-of-Antiquity validation bypasses.
- Hardware fingerprinting spoofing.
- Solana bridge (wRTC) contract issues.
- API authentication/authorization flaws.
- Denial of service vectors.
- Cryptographic weaknesses.

### Out of Scope

- Social engineering attacks (phishing, etc.) against Rustchain staff or users.
- Issues in third-party dependencies (please report these upstream).
- Issues requiring physical access to a user's hardware.
- Theoretical attacks without a functional Proof of Concept.
- UI/UX bugs or spelling errors that do not pose a security risk.

## Safe Harbor

We consider activities conducted consistent with this policy to constitute "authorized" conduct. We will not initiate legal action or law enforcement investigation against you for activities compliant with this policy. If legal action is initiated by a third party against you, we will make it known that your actions were conducted in compliance with this policy.

**To remain in Safe Harbor, you must:**
- Make a good faith effort to avoid privacy violations, destruction of data, and interruption or degradation of our service.
- Not exploit a vulnerability further than necessary to establish its existence.
- **Not leak, manipulate, or destroy user funds.** If a vulnerability exposes funds, you must report it immediately without exploiting it.

## Disclosure Policy

We follow a coordinated disclosure policy. We ask that you do not publicly disclose the vulnerability until a fix is deployed and we have mutually agreed on a disclosure timeline (typically within 90 days of the report). After patching, we will publish a security advisory crediting you for the discovery.
