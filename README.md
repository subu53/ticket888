# ticket888

## Marketing skills

This repo vendors the 49 marketing skills from [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) into `.claude/skills/`. Claude Code auto-discovers project skills there, so no extra setup is needed when working in this repo — skills like `seo-audit`, `copywriting`, `cro`, `ads`, etc. are available automatically.

Source license: MIT (Corey Haines) — see `.claude/skills/LICENSE-marketingskills`.

### Alternative ways to get these skills

- **Claude Code plugin marketplace** (in any repo, not just this one):
  ```
  /plugin marketplace add coreyhaines31/marketingskills
  /plugin install marketing-skills
  ```
- **skills CLI**:
  ```
  npx skills add coreyhaines31/marketingskills -a claude-code
  ```
- **Claude.ai chat / Cowork**: enable Code execution and file creation under Settings → Capabilities, then upload each skill individually as a ZIP under Customize → Skills → + (each ZIP must have a single skill folder at its root).
