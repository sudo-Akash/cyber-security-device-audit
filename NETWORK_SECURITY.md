# Network Security Assessment



## Wi-Fi Security



* Security type: WPA2-personal
* Assessment: secure home wi-fi encryption standard
* Risk level: low



## DNS Configuration



* DNS Server: 192.168.31.1
* Assessment: Router provided dns service
* Risk level: Low



## Router password strength



* Assessment: Medium password configured
* Risk level: low



## Guest network:

* Status: Not enabled
* Risk level: low

### 

### Summary



The network configuration appears secure. The wi-fi network uses WPA2-Personal encryption, DNS is provided through the local router, and no obvious security concerns were identified during the review.



## Network Risks Identified

### Weak passwords



Risk level: Medium

Finding:
The wi-fi password contains letters, numbers, and a second special character, but follows a somewhat predictable pattern.

Recommendation:
Use a longer password with a mix of uppercase letters, lowercase letters, numbers, and special characters.



### Open access points:



Risk level: low

Finding:
No open wi-fi networks detected. The network uses WPA2-Personal encryption.

Recommendation:
Continue using encrypted wi-fi access and avoid open networks.



## Outdated firmware:



Risk level: unknown

Finding:
Router administration access was not available during the assessment.

Recommendation:
Check periodically for firmware updates through the router administration page.

### 

### Missing protections



Risk level: low

Finding:
Guest network is not enabled.

Recommendation:
Enable a guest network if visitors frequently require internet access..

## 

## Overall assessment



The home network is generally secure. WPA2-Personal encryption is enabled, DNS is configured through the router, and no major security risks were identified. Minor improvements include strengthening the wi-fi password and periodically checking router firmware updates.



## Cloud backups



* Google account data is synchronized through Google services.
* Microsoft Onedrive backup is not configured

## 

## Local Backups



* No dedicated local backup solution identified.

## 

## Recovery procedures



* Google account data can be restored by signing into the account.
* Windows backup features are not currently configured.

## 

## Assessment

### Backup frequency



* Google account data syncs automatically.
* Windows backups are not  being performed.

## 

## Backup reliability



Medium - Low



### Recovery readiness



* Medium

## 

## Recommendations



i. Configure OneDrive backup or another cloud backup solution.
ii. Create periodic backups of important files to an external drive
iii. Store internship and academic documents in cloud storage

## 

## Device Encryption



Encryption technology: Bitlocker

Status: disabled

Assessment:
Bitlocker full disk encryption is not enabled on the system.

Risk level: Medium

Potential impact:
If the laptop is lost or stolen, data stored on the drive could potentially be accessed by unauthorized individuals.

Recommendation:
Enable Bitlocker to provide full disk encryption and improve protection of sensitive data.

