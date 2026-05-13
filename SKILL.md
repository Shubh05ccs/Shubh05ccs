---
name: "GitHub Profile Config"
description: "Config files for my GitHub profile. Provides README and helper files so Claude can discover and use this repository as a skill."
---

# SKILL file for Claude

This file satisfies Claude's packaging requirement: a top-level SKILL.md containing the skill name and description in YAML frontmatter. Include this file at the root of any .zip or .skill package you upload to Claude.

Packaging instructions

- To create a .zip containing SKILL.md and the repo contents:
  - git clone https://github.com/Shubh05ccs/Shubh05ccs
  - cd Shubh05ccs
  - zip -r ../Shubh05ccs.skill *

- Verify the package contains SKILL.md at the root:
  - unzip -l ../Shubh05ccs.skill | grep SKILL.md

Notes

- The YAML frontmatter at the top is exactly what Claude requires: keys `name` and `description`.
- If you want a different skill name or description, tell me and I will update SKILL.md accordingly.
