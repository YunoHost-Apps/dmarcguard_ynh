DMARCguard requires valid IMAP credentials to fetch DMARC aggregate reports.

Prepare before install:

1. Create a dedicated mailbox on your YunoHost mail server (for example `dmarc@yourdomain.tld`). It is recommended to use this mailbox only for DMARC reports.
2. Point your DMARC policy to this mailbox (`rua=mailto:dmarc@yourdomain.tld`).
3. Use this mailbox IMAP host/port and credentials during installation.

By default, processed messages are marked as read. You can also configure your mail server or mailbox rules to periodically delete read messages from this dedicated mailbox.
