# log-formatter-pro — lab sample (pedagogical only)

**Do not run** the install commands in `README.md`. This is a marketplace-vetting exercise artifact.

## Contents

| File | Purpose |
|------|---------|
| `skill.json` | OpenClaw-style manifest |
| `README.md` | Oversized install doc (size + patterns are intentional) |

## Invariants (lab blocklist / scanner)

- **Size:** `530103` bytes  
- **SHA256:** `c60243b5c996d11da2909dc4d201d012a0999fdb48e75e1674440be139eb96a3`

Verify after hosting:

```bash
wc -c skills/log-formatter-pro/README.md
sha256sum skills/log-formatter-pro/README.md
```

## Suggested GitHub layout

Push this folder so learners can `curl` the README, for example:

```text
your-repo/
  marketplace-vetting/
    log-formatter-pro/
      README.md
      skill.json
```

**Raw URL for step 1** (replace `ORG`, `REPO`, `BRANCH`):

```text
https://raw.githubusercontent.com/ORG/REPO/BRANCH/marketplace-vetting/log-formatter-pro/README.md
```

Or expose only the skill folder at repo root:

```text
your-repo/
  log-formatter-pro/
    README.md
    skill.json
```

Raw URL:

```text
https://raw.githubusercontent.com/ORG/REPO/BRANCH/log-formatter-pro/README.md
```

Send the working raw URL to update `step1.md` and `reference/fetch-log-formatter-pro-readme.sh`.