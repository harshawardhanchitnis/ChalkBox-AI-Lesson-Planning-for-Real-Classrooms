# ChalkBox Roadmap

ChalkBox is evolving from a hackathon-built classroom product into a maintainable open-source education project. The roadmap prioritizes reliability, contributor clarity, teacher usefulness, privacy, and source-grounded AI behavior.

## Near term

- Stabilize reproducible local/self-hosted setup.
- Expand automated tests for core lesson-planning, RAG, safety, and sharing flows.
- Improve contributor documentation and issue labeling.
- Establish tagged releases and release notes.
- Document architecture and trust boundaries for new contributors.
- Improve error handling and observability for optional AI/database integrations.
- Add accessibility review and keyboard/screen-reader improvements.

## Product and AI quality

- Improve retrieval quality, chunk selection, and source provenance.
- Add repeatable evaluation cases for grounded lesson generation.
- Strengthen science/classroom safety checks and regression tests.
- Improve graceful behavior when model calls, storage, or network access fail.
- Expand multilingual classroom terminology quality without weakening source grounding.

## Teacher experience

- Gather structured teacher feedback on lesson usefulness and preparation-time reduction.
- Improve low-resource classroom workflows.
- Refine Quick Teach, Present Mode, and assessment-generation workflows.
- Make lesson export and portability more robust.

## Open-source community

- Maintain beginner-friendly issues where appropriate.
- Improve contributor onboarding and development fixtures.
- Document extension points for additional subjects, curricula, languages, and model providers.
- Publish regular changelogs and release notes.

## Longer-term exploration

The following are exploratory and are not commitments:

- pluggable model/provider interfaces;
- additional curriculum adapters;
- privacy-preserving analytics;
- teacher-created reusable templates;
- optional offline-first inference/retrieval components where technically practical.

## Guiding principles

Roadmap items should preserve these constraints:

1. Teachers remain in control of generated material.
2. Source-grounded claims should retain provenance where applicable.
3. Private documents and credentials must not cross unauthorized trust boundaries.
4. Classroom safety is a product requirement, not an afterthought.
5. The demo and documentation should describe capabilities truthfully.

Suggestions are welcome through GitHub issues. Larger proposals should explain the classroom need, technical approach, privacy/safety implications, and expected maintenance cost.
