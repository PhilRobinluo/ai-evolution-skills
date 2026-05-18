# Skill Publishing Checklist

Before publishing a skill:

- [ ] `SKILL.md` has clear frontmatter with `name` and `description`.
- [ ] The skill does not contain private paths, secrets, private data, or local-only assumptions.
- [ ] Any scripts are deterministic enough to reuse.
- [ ] Examples are synthetic or safe to redistribute.
- [ ] README explains what the skill does in plain language.
- [ ] `registry.json` includes the skill.
- [ ] Run `tools/validate-skill.sh skills/<skill-name>`.

