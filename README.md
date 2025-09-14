# cybersecurity-notes
Running notes as I learn IT & Cybersecurity 

## DNS & Email Authentication (Completed)
- **SPF**: why it exists, sample record, how to validate (MXToolbox, Gmail “Show original”).
- **DKIM**: selectors, CNAMEs, enabling in M365, how to test.
- **DMARC**: p=none → quarantine → reject, reports mailbox, what reports look like.
- **MTA-STS & TLS-RPT**: purpose, policy URL, TXT records, basic validation.

> Detailed configuration write-up lives in my [`email-security-setup`](https://github.com/evan-margelos/email-security-setup) repo.

---

## Roadmap / Next Steps
These are the areas I’m actively working on and will add to this repo as I progress:

### Networking Fundamentals
- OSI vs TCP/IP (quick bullets)
- IP, ports, protocols (TCP/UDP)
- Subnets & CIDR (cheatsheet)

### Tools & Labs
- Wireshark: first capture, filtering basics (http, dns)
- Nmap: scan types (-sS, -sV, -O) on localhost/lab
- Windows Event Viewer: Security/System log review

### HackTheBox Journal
- Meow (to be documented in [HackTheBox Journal repo]
- Fawn (to be documented in [HackTheBox Journal repo]
