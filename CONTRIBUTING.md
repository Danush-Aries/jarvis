# Contributing

Thanks for taking the time to contribute!

## How to contribute
1. **Fork** the repo and create a branch (`git checkout -b feat/my-change`)
2. **Code** — keep changes focused, add tests where behaviour changes
3. **Commit** with a clear message (prefix: `feat:`, `fix:`, `docs:`, `test:`)
4. **Push** and open a Pull Request against `main`
5. **CI** must be green before merge (GitHub Actions runs automatically)

## Style
- Python: `ruff` + `pytest` (installed via `pip install -e ".[dev]"`)
- TypeScript: follow existing `tsc` strict settings
- Keep README badges and docs in sync with behaviour changes

## Questions?
Open a GitHub Discussion for ideas, or an Issue for bugs. Report security issues privately via the repo's Security tab instead of a public issue.
