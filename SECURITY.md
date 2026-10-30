# Security Policy

These projects include cryptographic and network code (TeamSpeak 3 handshake and
packet crypto on mbedTLS, Opus voice packets).

## Reporting a vulnerability

Do not open a public issue. Instead:

- Use GitHub's private vulnerability reporting (the repo's Security tab -> *Report a vulnerability*), or
- email cipheraenys@gmail.com.

Include the repo, the affected version or commit, and how to reproduce. Expect an
initial response within about a week. Please allow time for a fix before public disclosure.

## Scope

In scope: memory safety on untrusted server input (command parsing, fragment
reassembly, QuickLZ decompression), crypto misuse, and key / entropy handling.

Out of scope: issues that need physical device access.
