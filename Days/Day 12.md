# Day 12 - HTTPS


## Key Learnings

- HTTPS encrypts the conversation so only your browser and the server can read it
- HTTPS protects the channel, not the destination
- browser and the server agreed on encryption, server presented a certificate, trusted third party vouched for that certificate
- Anyone can get a free certificate for a domain in five minutes. The bar to clear is "I control this domain," not "I am trustworthy." Ex. lets encrypt
- When a CA fails, every padlock signed by it instantly becomes a lie
- Read URLs from right to left, not left to right — the rightmost dot tells you who actually owns it
- DigiNotar story — the case study you'll see referenced in real security reports for years to come
- ssllabs.com/ssltest - get back a graded report — A+, A, B, C, or worse. Below the grade, the report breaks down exactly which TLS versions the site supports, which ciphers, whether it has known vulnerabilities, and how its certificate chain is configured
