# log-formatter-pro — lab sample (pedagogical only)

**Do not run** the install commands in `README.md`. This is a marketplace-vetting exercise artifact.

## Contents

| File | Purpose |
|------|---------|
| `skill.json` | OpenClaw-style manifest |
| `README.md` | Oversized install doc (size + patterns are intentional) |

## Invariants (lab blocklist / scanner)

- **Size:** `530103` bytes  
- **SHA256:** `1d3b124b1c3dbf9c06e99109a399babf96f8d58bb713c011b96c7db69319e5b2`

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

**Live mirror:** [Ractorrr/malicious_skills](https://github.com/Ractorrr/malicious_skills/tree/main/log-formatter-pro) — raw URL used in `step1.md`.
