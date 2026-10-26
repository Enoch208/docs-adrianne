# Selo documentation

Source for the Selo docs site, built with [Mintlify](https://mintlify.com) and published at
[selo.mintlify.site](https://selo.mintlify.site).

Selo is CI for x402: it pays your endpoint before your users do. The product lives at
[useselo.xyz](https://useselo.xyz) and its code at
[github.com/Enoch208/selo](https://github.com/Enoch208/selo).

## Layout

| Path | What it holds |
| --- | --- |
| `docs.json` | Site configuration and navigation |
| `index.mdx`, `quickstart.mdx`, `how-it-works.mdx`, `agents.mdx` | Get started |
| `guides/` | Task guides: authorize, preflight, contract, release test, GitHub Actions, verify, resume |
| `concepts/` | How the checks, verdicts, payments, authorization, attestations and security work |
| `resources/` | Pricing and limits, Mainnet proof, FAQ, limitations, changelog |
| `cli/` | `selo` CLI and GitHub Action reference |
| `api-reference/` and `openapi.json` | HTTP API reference |

## Preview locally

```bash
npx mint dev
```

Then open http://localhost:3000. Check links before pushing:

```bash
npx mint broken-links
```

Pushing to `main` publishes the site.
