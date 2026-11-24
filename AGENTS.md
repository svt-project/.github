# Agent guidance

- Use American English. Work serially; request approval before delegating.
- Check Git status before editing and preserve unrelated changes. Default branch: `master`.
- This is the public organization profile and coordination repository. GitHub issues own migration
  plans and delivery tracking; repository documents describe current responsibilities.
- Keep specification rules and canonical conformance reference assets in `svt-spec`, and .NET
  implementation details in `svt-dotnet`. Implementations embed
  explicitly accepted, stamped asset snapshots; do not use live specification dependencies.
  Keep the cookbook independent, with polished examples and bespoke resources. Do not create
  duplicate authoritative specifications; stamped implementation test copies are intentional.
- Keep specification prose in its Git repository. The `svt-project.github.io` repository owns the
  project site, `/ns/svt` reference page and future `/cookbook/` content directly; link other
  repositories without copying their authoritative content. Cookbook and TypeScript implementation
  work are separate follow-ups.
- Discuss consequential format, namespace, package, dependency, or ownership decisions before
  implementation. Repository relocation does not authorize package publication or format changes.
- Keep machine paths, IDE metadata, agent transcripts, credentials, and generated evidence out of
  commits and public issues. Local handoff notes belong in ignored `.local/`.
- Preserve copyright and third-party attribution. Bathos is the founding maintainer; independent
  project branding does not remove existing legal notices.
- Validate Markdown formatting and links before committing. Review the staged diff for private data.
- A local checkout may be named `dot-github`; the remote repository name remains `.github`.
