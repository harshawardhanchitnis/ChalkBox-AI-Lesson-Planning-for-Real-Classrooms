# Contributing to ChalkBox

Thanks for helping improve ChalkBox. Contributions are welcome from developers, educators, testers, accessibility reviewers, and documentation contributors.

## Before you start

- Read the README and open issues before proposing a large change.
- Keep changes focused and explain the classroom or maintainer problem they solve.
- Never commit API keys, credentials, learner names, student PII, copyrighted textbook files, or private teacher content.
- AI-assisted contributions are welcome, but contributors remain responsible for reviewing, testing, and understanding the submitted code.

## Development setup

### Prerequisites

- Node.js 20+
- pnpm
- Git

### Local setup

```bash
git clone https://github.com/harshawardhanchitnis/ChalkBox-AI-Lesson-Planning-for-Real-Classrooms.git
cd ChalkBox-AI-Lesson-Planning-for-Real-Classrooms
pnpm install
cp .env.example .env
pnpm dev
```

The prepared/local-first demo should remain usable without production credentials. Optional integrations may require owner-provided environment variables; never commit real values.

## Quality checks

Before opening a pull request, run the checks available for your change:

```bash
pnpm lint
pnpm build
```

If you add or modify tests, run the relevant test commands documented by the project and include the results in the pull request description.

## Contribution workflow

1. Fork the repository or create a feature branch.
2. Create or reference an issue for non-trivial changes.
3. Use a descriptive branch name such as `feat/lesson-export` or `fix/source-provenance`.
4. Keep commits focused and use clear messages.
5. Update documentation when behavior, configuration, or user workflows change.
6. Open a pull request using the repository template.
7. Respond to review feedback and keep the PR scoped.

## Good contribution areas

- Classroom workflow and teacher UX
- RAG retrieval quality and source provenance
- Science/classroom safety checks
- Accessibility and low-resource classroom support
- Offline/PWA reliability
- Test coverage and CI hardening
- Documentation and self-hosting
- Internationalization and terminology quality

## Pull request expectations

A strong pull request should include:

- the problem being solved;
- a concise summary of the implementation;
- screenshots or recordings for UI changes;
- test/build/lint evidence where applicable;
- privacy, security, safety, or copyright considerations;
- documentation updates when needed.

Maintainers may request changes, split an oversized PR, or decline changes that conflict with ChalkBox's teacher-first, privacy-aware scope.

## Reporting security issues

Do not open a public issue for a vulnerability that could expose credentials, private content, authentication flows, or user data. Follow `SECURITY.md` instead.

## License

By contributing, you agree that your contributions will be licensed under the repository's Apache License 2.0.
