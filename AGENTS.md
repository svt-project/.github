# Agent guidance

- Use American English. Work serially; request approval before delegating.
- Check Git status before editing and preserve unrelated changes. Default branch: `master`.
- This is the public organization profile and coordination repository. GitHub issues own migration
  plans and delivery tracking; repository documents describe current responsibilities.
- Keep specification rules and cookbook content in `svt-spec`, and .NET implementation details in
  `svt-dotnet`, once those repositories exist. Do not create duplicate authoritative specifications.
- Discuss consequential format, namespace, package, dependency, or ownership decisions before
  implementation. Repository relocation does not authorize package publication or format changes.
- Keep machine paths, IDE metadata, agent transcripts, credentials, and generated evidence out of
  commits and public issues. Local handoff notes belong in ignored `.local/`.
- Preserve copyright and third-party attribution. Bathos is the founding maintainer; independent
  project branding does not remove existing legal notices.
- Validate Markdown formatting and links before committing. Review the staged diff for private data.
- A local checkout may be named `dot-github`; the remote repository name remains `.github`.
