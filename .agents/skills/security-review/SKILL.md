---
name: security-review
description: Use this skill to identify and prevent common application security problems.
---

# security-review

Purpose:
Identify and prevent common application security problems.

Instructions:
- Never expose secrets, API keys, passwords, tokens, private keys, or credentials.
- Never hardcode secrets.
- Prefer environment variables or the project's secure configuration mechanism.
- Check for accidental secret exposure.
- Check authentication and authorization boundaries.
- Check input validation.
- Check unsafe file/path handling.
- Check SQL injection risks.
- Check command injection risks.
- Check insecure deserialization.
- Check dangerous dependency usage.
- Check sensitive information in logs.
- Check overly permissive CORS/configuration when relevant.
- Do not weaken security controls simply to make development easier.
- Never commit secret-containing .env files.
