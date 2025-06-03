# System Hardening Win 11
WIN 11 system hardening check list. A series of powershell codes to run to make sure your Windows 11 is safe.

- Save each snippet as a .ps1 file (e.g., Disable-SMBv1.ps1, Enforce-PasswordPolicy.ps1, etc.).
- Run as Administrator in an elevated PowerShell console.
- Reboot after major changes (SMBv1, services, telemetry).
- Test carefully—some commands (especially service removals or app removals) can break features if you actually need them. Always try in a lab or VM first.
- Schedule periodic reviews to verify these settings haven’t been reverted by Windows updates.

