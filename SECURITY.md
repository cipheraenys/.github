# Security Policy

These projects include cryptographic and network code (the TeamSpeak 3 handshake,
mbedTLS primitives, Opus / RTP). Security reports are welcome.

## Reporting a vulnerability

Please do **not** open a public issue. Instead:

- Use GitHub's private vulnerability reporting (the repo's **Security** tab -> *Report a vulnerability*), or
- email cipheraenys@gmail.com.

Include the repo, the affected version or commit, and how to reproduce. Expect an
initial response within about a week. Please allow time for a fix before public disclosure.

## Scope

In scope: memory safety on untrusted server input (command parsing, fragment
reassembly, QuickLZ decompression), crypto misuse, and key / entropy handling.

Out of scope: issues that need physical device access, and the device-dump or
vendor-firmware notes kept under gitignored paths.
