# honest-scholar-docs

The rendered documentation site for
[**honest-scholar**](https://github.com/davorrunje/honest-scholar), built with
[Mintlify](https://mintlify.com) and served at
[honest-scholar.science](https://honest-scholar.science).

> **This repo is a build target, not a source of truth.** The documentation
> *content* lives as markdown in the main
> [`honest-scholar`](https://github.com/davorrunje/honest-scholar) repository. The
> plan (see its `docs/design/proposals/docs-site.md` and ADR-0030) is for that
> repo's CI to **generate** this site — assembling the user guide, skills, the
> `honest-scholar` CLI reference, and the design record — and push it here on
> release, where Mintlify redeploys it. Until that pipeline lands, this holds a
> placeholder landing page.

## Contents

- `docs.json` — Mintlify site configuration (theme, colors, navigation).
- `index.mdx` — the landing page.
- `wordmark.svg` — the logo.

## Local preview

```bash
npm i -g mint
mint dev
```

## License

[Apache-2.0](LICENSE) — © 2023–2026 Davor Runje.
