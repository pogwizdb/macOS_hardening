# macOS Security Audit Tool

Read-only macOS security auditing and posture assessment script.

The tool does NOT modify system configuration.
It performs local security checks and reports:
- enabled protections
- insecure settings
- exposed services
- privacy-impacting features

## Features

- Firewall checks
- SIP / Secure Boot validation
- FileVault verification
- Sharing & remote access audit
- Privacy configuration checks
- System service inspection

## Preview

![Preview](preview.png)

## Usage

```bash
chmod +x auditMAC.sh
./auditMAC.sh
```

## Requirements

- macOS
- Administrator privileges (sudo)

## Author

Bartłomiej Pogwizd  
YouTube: [pTech](https://youtube.com/@pTech-pl)

## Disclaimer

This script is provided for educational and auditing purposes only.
This tool does not modify system settings.
It performs read-only local security auditing.
Always review scripts before running them with elevated privileges.
The author is not responsible for any damage or misconfiguration caused by the use of this script.
