DMARCguard requires valid IMAP credentials to fetch DMARC aggregate reports.

Prepare before install:

1. Create a dedicated mailbox on your YunoHost mail server (for example `dmarc@yourdomain.tld`).
2. Point your DMARC policy to this mailbox (`rua=mailto:dmarc@yourdomain.tld`).
3. Use this mailbox IMAP host/port and credentials during installation.
