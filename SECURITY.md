# Security Policy

ChalkBox handles AI-generated content and may be configured with authentication, private document storage, database access, sharing, and external model APIs. Please report security problems responsibly.

## Supported versions

The project is currently early-stage. Security fixes are applied to the latest version on the default branch and to the most recent tagged release when practical.

## Reporting a vulnerability

Please **do not open a public GitHub issue** for vulnerabilities that could expose:

- API keys, tokens, or credentials;
- authentication or authorization weaknesses;
- private teacher documents or uploaded textbook content;
- user or learner data;
- database/storage access;
- share-token or access-control bypasses;
- prompt-injection paths that can cross a trust boundary;
- dependency or deployment weaknesses with a credible exploit path.

Contact the primary maintainer privately using a contact method listed on the maintainer's GitHub profile. Include:

1. a concise description of the issue;
2. affected component and version/commit;
3. reproducible steps or proof of concept;
4. likely impact;
5. suggested mitigation, if known.

Please avoid accessing or retaining data that is not yours. Do not use a vulnerability to disrupt a live deployment.

## Disclosure

After a report is validated, the maintainer will work to reproduce and remediate it and will coordinate public disclosure when a fix is available. Credit will be given to reporters who want attribution, unless disclosure would create additional risk.

## Security principles

Contributions should preserve ChalkBox's trust boundaries: secrets remain server-side, private source material stays scoped to the authorized user, learner PII is not required, generated content is treated as untrusted until validated, and public sharing must not expose private records.
