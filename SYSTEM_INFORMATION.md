# Final Security Audit

## System Information



Operating System: Windows 11
OS version: 25H2
RAM: 8 GB
Storage capacity: 238 GB
Processor: AMD Ryzen 5 PRO 3500 w/ Radeon Vega Mobile Gfx



## Installed Applications

|Application Name|Purpose|Risk level|
|-|-|-|
|Google Chrome|Web browsing|Low|
|MS Edge|Web browsing|Low|
|Outlook|Email|Low|
|Cisco Packet Tracer|Network simulation|Low|
|Oracle Database 21c Express Edition|Database management|Medium|
|Claude|AI assistant|Low|
|EmEditor|Text Editing|Low|
|AMD Software|Graphics driver management|Low|
|HP System information|Device diagnostics|Low|
|Paint|Image editing|Low|

## Unused Applications

|Application Name|Reason|
|-|-|
|Maps|Never used|
|People|Never used|
|Paint 3d|Never used|
|Clock|Never used|
|MS Copilot|Never used|

## Potentially risky applications

|Application Name|Purpose|Risk level|
|-|-|-|
|Oracle Database 21c Express Edition|Database server|Medium|
|Outlook|Email|Medium|
|MS Copilot|AI assistant|Medium|
|MS 365 Copilot|AI assistant|Medium|



## Password Exposure Assessment

I checked my Email address using  Have I Been Pawned.

Breaches found: 0

Affected services: 0

Actions taken:

* Verified no breaches were associated with the checked email address
* Continued use of strong passwords
* Recommended maintaining unique passwords and enabling multi-factor authentication (MFA)



## Password Security Assessment



### Password Length

Most passwords are longer than 8 characters. However, the password manager identified 14 weak passwords that should be strengthened.



### Password Uniqueness

Password checkup identified 8 reused passwords across multiple accounts. Reusing passwords increases the risk of credential stuffing attacks.



### MFA Usage

Multi-Factor Authentication (MFA) is enabled on critical accounts where available.



### Password Length

Most passwords are longer than 8 characters. However, the password manager identified 14 weak passwords that should be strengthened.



### Password Uniqueness

Password checkup identified 8 reused passwords across multiple accounts. Reusing passwords increases the risk of credential stuffing attacks.



### MFA Usage

Multi-Factor Authentication (MFA) is enabled on critical accounts where available.



### Password Manager Usage

Google Password Manager is used to store and manage account  credentials.



### Password Checkup Results

Compromised passwords: 0

Reused passwords: 8

Weak passwords: 14



### Findings

No compromised passwords were detected. However, several passwords are reused across multiple accounts and some passwords are considered weak



### Recommendations

* Replace weak passwords with stronger passwords of at least 12 characters
* Use unique passwords for each account.
* Continue using a password manager to generate and store secure passwords.
* Enable Multi Factor Authentication where available.



## Malware Protection Asssessment



### Security Software

Microsoft Defender



### Scan Type

Full System Scan



### Scan Date

02 June 2026



### Scan Duration

2 minutes 22 seconds



### Files scanned

28,586



### Threats Detected

0



### Actions Taken

No action required. No malware or suspicious files were detected.



### Conclusion:

MS Defender is active, updated and successfully completed a full system scan  with no threats identified.





## File reputation check



### File analyzed

ClaudeSetup.exe



### Detection results

1 out of 59 security vendors flagged the file as suspicious.



### Vendor analysis

Most security vendors classified the file as safe. Only one vendor reported a malware detection.



### Reputation assessment

The file appears to be legitimate and trusted. The single detection is likely a false positive because the application originates from a reputable source and is widely used.



### Conclusion

ClaudeSetup.exe is considered safe for use despite a single vendor detection. Further investigation would be recommended in a professional environment.



## Browser Security Assessment

### Safe settings

\-Safe Browsing enabled
-Google Password Manager enabled
-Password breach monitoring enabled
-Multi-Factor Authentication (MFA) enabled
-Only one browser extension installed (Google Docs Offline)

### Risky settings

\-Third-party cookies are currently allowed
-8 reused passwords identified
-14 weak passwords identified

### Installed Extensions

|Extension|Purpose|Risk Level|
|-|-|-|
|Google Docs Offline|Allows offline editing of Google documents|Low|

### Recommended improvements

\-Replace weak passwords with stronger passwords
-Use unique passwords for all accounts
-Consider blocking third-party cookies
-Continue using MFA on important accounts
-Periodically review installed extensions

