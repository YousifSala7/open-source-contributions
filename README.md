# Open Source Contributions

A log of my merged contributions to open-source projects.

## [Fallout.build](https://github.com/Fallout-build/Fallout)

> A C#/.NET build automation framework (successor to NUKE).

### Merged Pull Requests

- **[#514 – Rename legacy prefixed private fields to camelCase](https://github.com/Fallout-build/Fallout/pull/514)**
  - Led a structural refactoring across 89 source files to enforce modern C# naming conventions.
  - Debugged and fixed a CI failure caused by a reflection-based JSON converter relying on a hardcoded field name.

- **[#493 – Fixed invalid YAML emission in CI writers](https://github.com/Fallout-build/Fallout/pull/493)**
  - Corrected single-quote escaping logic in GitHub Actions and Azure Pipelines configuration generators.
  - Added snapshot-based regression tests using `Verify.Xunit` to prevent regressions.
