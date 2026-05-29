# B1 – Discover 5 Unique Weak/Vulnerable Security Implementations

## Introduction

Cybersecurity vulnerabilities often arise from weak security implementations rather than advanced attacks. This activity investigates five common vulnerable security implementations, explains why they are insecure, discusses their potential impacts, and provides recommendations for mitigation.

---

# 1. Default Credentials

## Description

Many routers, IP cameras, and Internet of Things (IoT) devices are shipped with default usernames and passwords such as `admin/admin` or `admin/password`. Users often fail to change these credentials after installation.

## Why It Is Vulnerable

Default credentials are publicly documented and can be easily found online by attackers.

## Potential Impact

* Unauthorized access to devices
* Network compromise
* Device takeover
* Data exposure

## Recommended Mitigation

* Change default passwords immediately after installation
* Use strong and unique passwords
* Enable multi-factor authentication where available

## Evidence

See supporting evidence in the evidence folder.

---

# 2. Use of HTTP Instead of HTTPS

## Description

Some websites still use HTTP instead of HTTPS for communication. HTTP does not encrypt data transmitted between users and websites.

## Why It Is Vulnerable

Attackers can intercept and read information transmitted over HTTP connections.

## Potential Impact

* Credential theft
* Session hijacking
* Exposure of sensitive information
* Man-in-the-middle attacks

## Recommended Mitigation

* Enforce HTTPS across all web pages
* Use TLS certificates
* Implement HSTS policies

## Evidence

See supporting evidence in the evidence folder.

---

# 3. Weak Password Policies

## Description

Some systems allow users to create simple and predictable passwords such as `password123`, `12345678`, or `qwerty123`.

## Why It Is Vulnerable

Weak passwords can be guessed through brute-force attacks or dictionary attacks.

## Potential Impact

* Unauthorized account access
* Identity theft
* Data breaches
* Privilege escalation

## Recommended Mitigation

* Enforce strong password requirements
* Require longer passwords or passphrases
* Implement multi-factor authentication
* Encourage the use of password managers

## Evidence

See supporting evidence in the evidence folder.

---

# 4. Hardcoded Secrets in Source Code

## Description

Developers sometimes store API keys, passwords, authentication tokens, or database credentials directly in source code.

## Why It Is Vulnerable

If the source code is exposed or uploaded to a public repository, attackers can obtain sensitive credentials.

## Potential Impact

* Unauthorized system access
* Data theft
* Abuse of cloud resources
* Financial losses

## Recommended Mitigation

* Store secrets in environment variables
* Use secret management systems
* Rotate credentials regularly
* Scan repositories for exposed secrets

## Evidence

See supporting evidence in the evidence folder.

---

# 5. Outdated and Unpatched Software

## Description

Organizations sometimes continue using software versions that no longer receive security updates and patches.

## Why It Is Vulnerable

Known vulnerabilities remain exploitable because security fixes are unavailable or have not been applied.

## Potential Impact

* Malware infections
* Remote code execution
* Data breaches
* System compromise

## Recommended Mitigation

* Maintain a patch management process
* Upgrade unsupported software
* Conduct regular vulnerability assessments
* Monitor vendor security advisories

## Evidence

See supporting evidence in the evidence folder.


