1. Default Credentials

Evidence: NETGEAR default login credentials screenshot.

The screenshot shows that many NETGEAR devices ship with default usernames and passwords such as:

Username: admin
Password: password
Password: 1234

Using default credentials is a significant security weakness because attackers are aware of these commonly published values and can easily gain unauthorized access if users fail to change them.

Security Risk:

Unauthorized device access
Router compromise
Network takeover
2. Hardcoded Secrets in Source Code

Evidence: config.py containing API keys and passwords.

The configuration file contains sensitive credentials directly embedded in the source code, including:

API keys
Database passwords
AWS access keys

Hardcoding secrets into applications is a serious security vulnerability because anyone with access to the code repository can obtain these credentials and potentially access protected systems.

Security Risk:

Credential theft
Cloud resource compromise
Data breaches
3. Insecure HTTP Communication

Evidence: neverSSL screenshots showing "Not Secure" connection.

The screenshots demonstrate a website using HTTP instead of HTTPS. Modern browsers warn users that the connection is not secure because information transmitted over HTTP is not encrypted.

Without encryption, attackers can intercept network traffic and potentially steal sensitive information.

Security Risk:

Man-in-the-middle attacks
Credential theft
Data interception
4. Weak Password Usage

Evidence: NordPass password statistics and example account password.

The evidence shows commonly used passwords such as:

admin
password
123456
qwerty123

Additionally, the example account uses the weak password:

password123

Weak passwords are easily guessed through dictionary attacks and brute-force attacks.

Security Risk:

Account compromise
Credential stuffing attacks
Unauthorized access
5. End-of-Life Operating System

Evidence: Microsoft Windows 8.1 End-of-Support screenshots.

The screenshots show that Windows 8.1 reached end-of-support on 10 January 2023 and no longer receives:

Security updates
Bug fixes
Technical support

Running unsupported operating systems leaves systems exposed to newly discovered vulnerabilities that will never be patched.

Security Risk:

Increased malware exposure
Unpatched vulnerabilities
Higher likelihood of successful cyberattacks
Conclusion

This investigation identified five vulnerable security implementations:

Default credentials
Hardcoded secrets
HTTP without encryption
Weak passwords
End-of-life operating systems
