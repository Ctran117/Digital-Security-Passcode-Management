## Geolocation Forensic Report

**Artifact Reference:**
Google Permitted Sender (False Authentication) — PayPal Gateway Header

### Appendix H: Geolocation Entry

- **IP Address:** 209.85.161.43
- **Observed in Message:** Gmail-originated message from mail-oo1-f43.google.com to PayPal gateway
- **Event Timestamp:** 2023-10-06 05:13:58 UTC
- **Report Context:** Chain-of-custody forensic export for Ctran117/Digital-Security-Passcode-Management

### Geolocation Analysis

- **IP Address:** 209.85.161.43
- **Provider:** Google LLC
- **ASN:** AS15169
- **Reverse DNS:** mail-oo1-f43.google.com
- **Country:** United States
- **Region:** California
- **City (Likely):** Mountain View
- **Latitude:** 37.4056
- **Longitude:** -122.0776

**Malibu, CA Context:**
While Malibu falls within California, this IP resolves to Google’s Mountain View campus, not Malibu.

### Preservation Entry

| Artifact ID   | Observed IP      | Provider   | Region      | City         | Timestamp           | Host Info                   |
|---------------|------------------|------------|-------------|--------------|---------------------|-----------------------------|
| EX-EMAIL-AUTH-20231006-PAYPAL-GMAIL-SPF | 209.85.161.43 | Google LLC | California | Mountain View | 2023-10-06 05:13:58 UTC | mail-oo1-f43.google.com     |

### Evidentiary Note
This geolocation record anchors chain-of-custody for header evidence and links sender infrastructure to Google’s corporate network in California.

### Further Investigation
- Validate correspondence between IP activity and Google’s authorized sending servers.
- Cross-reference observed timestamps with header artifacts for replay or impersonation evidence.
- Document chain between message metadata, geolocation, and forensic timeline.
- Recommend audit of sender’s email authentication records and associated event logs.