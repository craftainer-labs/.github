# craftainer-labs

Products built on the [craftainer](https://github.com/craftainer) templates.

Where `craftainer` holds starter templates, this org holds the apps made
from them. Everything here is **in development**: nothing below has a
release yet, and plans can change.

## What is planned

- **Kubernetes operators.** Five operators that share one library,
  `lib-operator-go`, for lifecycle, status and CRD conventions.
- **A GitHub App** that connects repositories to artifact and deploy
  platforms.
- **A call and dependency graph CLI** for Python, TypeScript and Rust
  code bases.

## Built on craftainer templates

Each product starts from a template, so its devcontainer, CI, hooks and
template-sync come from the same place:

- [`template-base`](https://github.com/craftainer/template-base), the
  frame every repo starts from.
- [`template-fastapi`](https://github.com/craftainer/template-fastapi),
  [`template-axum`](https://github.com/craftainer/template-axum) and
  [`template-react`](https://github.com/craftainer/template-react) for
  runtimes that exist today. Go and Kubernetes operator templates are
  planned in `craftainer`.

## License

The craftainer templates stay GPL-3.0-only. Products in this org that
are built from them are released under Apache-2.0 by the templates' sole
copyright holder.

## Contributing and security

See [CONTRIBUTING.md][contributing], the [Code of Conduct][coc] and
[SECURITY.md][security]. Report vulnerabilities privately, never in a
public issue.

> **Built AI-assisted.** These repos are developed with Claude Code.

[contributing]: https://github.com/craftainer-labs/.github/blob/main/CONTRIBUTING.md
[coc]: https://github.com/craftainer-labs/.github/blob/main/CODE_OF_CONDUCT.md
[security]: https://github.com/craftainer-labs/.github/blob/main/SECURITY.md
