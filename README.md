# mStable Apps

Web frontends for interacting with the mStable contracts.

---
## Apps

This repository comprises multiple mStable apps, all built using common libraries and a common UI.

| Status | Name               | Nx project | Port  |
|--------|--------------------|------------|-------|
| ✅      | (example app)      | `example`  | 3100 |
| ✅      | mStable Protocol   | `protocol` | 3000 |
| 🏗      | mStable Governance | `// TODO`  |      |
| 🧠      | ...more            |            |      |

---

## Development

This project was generated using [Nx](https://nx.dev).

### Quickstart

```bash
yarn
yarn nx serve --parallel --all
```

### Running an app

```bash
yarn nx run protocol:serve
```

### Building an app

```bash
yarn nx run protocol:build
```
