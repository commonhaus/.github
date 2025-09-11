# Security Policy

The Commonhaus Foundation takes security seriously.
We appreciate your help in keeping our projects, infrastructure, and community safe.

This policy describes how to report vulnerabilities, what is in scope, and how we respond.
Member projects may also provide their own `SECURITY.md` files; when they do, those take priority for project-specific issues.

## Reporting Security Issues

### For Member Projects

Each Commonhaus project manages its own security process. Please follow the instructions provided by the project.
A project’s `SECURITY.md` (or its GitHub organization-level policy) is the authoritative source for how that project handles vulnerabilities.

Projects may use their `SECURITY.md` to define:

- What kinds of issues they will respond to (e.g., severity thresholds)
- Expected time frames (for acknowledgement, assessment, patching)
- What kinds of external contributions are welcome or required (e.g., proof of concept, tests)
- What kinds of obligations they do *not* commit to (e.g., guaranteed CVE issuance, or patching under embargo)

Examples:

- **Hibernate**: [Hibernate Security Policy](https://github.com/hibernate/.github/blob/main/SECURITY.md)
- **Jackson**: [Jackson GitHub repository](https://github.com/FasterXML/jackson/blob/main/SECURITY.md)
- **JReleaser**: [JReleaser GitHub repository](https://github.com/jreleaser/jreleaser/blob/main/SECURITY.md)
- **Other projects**: Check the project’s `SECURITY.md`

For a full list of member projects, see our [projects page](https://www.commonhaus.org#our-projects).

### For Foundation Infrastructure

If you find a security issue in the Foundation’s infrastructure, automation, or websites, please contact us directly by emailing [security@commonhaus.org](mailto:security@commonhaus.org).
Include a clear description of the issue, steps to reproduce, the potential impact, and your preferred contact information.

Please do not open public issues for suspected vulnerabilities.

## Handling Reports

We aim to handle reports quickly and responsibly.
Our goal is to acknowledge reports within 48 hours and provide an initial assessment within 5 business days.
Actual response times may vary depending on severity, available capacity, and whether the issue affects multiple projects.
Progress updates are provided as remediation proceeds, and disclosure is coordinated with the reporter, with credit unless anonymity is requested.

### Disclosure and Embargoes

By default, Commonhaus and its member projects do not impose secrecy on reported security issues.
Reports will generally become public once a fix is available and confirmed.
In exceptional cases — such as when downstream users require time to update or when disclosure could cause immediate harm — a short embargo may be considered.
These embargoes are not guaranteed, depend on capacity, and will be clearly communicated if applied.

### Expectations for Reporters

We ask reporters to understand that many maintainers are volunteers or have limited resources.
Reports that include clear steps, proof-of-concept, or test cases greatly speed assessment and resolution.
Respecting the workload of maintainers helps the community overall.

### Transparency

To give users visibility, Commonhaus or member projects may document their security backlog or status when possible.
Where a project adopts no-embargo policies or specific maintenance terms, those should be clearly visible in the project’s repository.

## Scope

This policy applies to Foundation-wide assets and systems, including our websites (`commonhaus.org`), automation and tooling, and governance systems.

It does not cover individual member project codebases (report directly to those projects) or third-party services used by the Foundation (report to those vendors).

## Security Best Practices

We encourage all community members to keep dependencies updated, use secure coding and review practices, report vulnerabilities responsibly, and follow each project’s own security guidelines.

## Related Policies

Security reports and handling are guided by our broader governance framework:

- [Code of Conduct](https://www.commonhaus.org/policies/code-of-conduct/)
- [Conflict of Interest Policy](https://www.commonhaus.org/policies/conflict-of-interest/)
- [Intellectual Property Policy](https://www.commonhaus.org/policies/ip-policy/)
- [Trademark Policy](https://www.commonhaus.org/policies/trademark-policy/)

## Questions

For general questions (not for reporting vulnerabilities), email [hello@commonhaus.org](mailto:hello@commonhaus.org) or join our [Foundation discussions](https://github.com/commonhaus/foundation/discussions).
