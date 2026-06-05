# MESAx8 - Commit Message Convention

Format: `type(scope): short description`

The scope is optional but recommended for bigger projects.

---

## Types

| Type | When to use |
|------|-------------|
| `feat` | New circuit, block, or ISA addition (ALU, decoder, new instruction, ...) |
| `fix` | Fixing a bug or incorrect behavior in a design |
| `refactor` | Reworking a circuit without changing its function |
| `remove` | Removing a circuit, block, or instruction |
| `docs` | Changes to documentation only (instructions.txt, README, ...) |
| `chore` | Repo maintenance (LICENSE, .gitignore, folder structure, ...) |
| `wip` | Work in progress — incomplete, not yet functional |

---

## Scopes (examples)

`arch`, `alu`, `cu`, `pc`, `reg`, `bus`, `isa`, `flags`, `decoder`, `memory`, `io`

- `arch` — changes affecting the overall MESAx8 architecture (bus width, addressing model, high-level design decisions, ...)

---

## Examples

```
feat(alu): add overflow detection logic
fix(flags): correct carry flag behavior on SBB
refactor(cu): simplify microcode decoder layout
docs(isa): document indirect addressing instructions
feat(reg): add general-purpose register file
wip(alu): shifter not yet connected to output bus
chore: add MIT license and .gitignore
remove(isa): drop XCHG, replaced by two MOVs
```

---

## Notes

- Use **present tense**: "add" not "added"
- Keep the description **short** (under 72 chars)
- If more context is needed, add a blank line and a longer body below
