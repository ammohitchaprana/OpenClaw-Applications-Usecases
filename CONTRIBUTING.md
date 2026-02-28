# 🤝 Contributing to OpenClaw Applications & Use Cases

Thank you for helping make this the most comprehensive collection of OpenClaw use cases!

## Adding a New Use Case

### Step 1: Create a Use Case File

Create a new markdown file in the `/usecases/` folder:

```
usecases/your-use-case-name.md
```

### Step 2: Follow This Template

Your use case should cover these points:

```markdown
# Your Use Case Name

Brief one-line description of what this does.

## Pain Point

What problem does this solve? Why is this useful?

## What It Does

- Key feature 1
- Key feature 2
- Key feature 3

## Skills You Need

- [skill-name](https://clawhub.ai/author/skill-name) — Brief description of the skill
- Any other required tools or APIs

## How to Set It Up

1. Install required skills:
   ```bash
   clawhub install skill-name
   ```

2. Add to your OpenClaw agent instructions:
   ```text
   Your prompt/configuration here
   ```

3. Any additional setup steps

## Real World Example

**You:** "Example message to your agent"

**OpenClaw:** "Example response showing the use case in action"

## Variations

- Alternative approaches or extensions
- Advanced configurations

## Key Insights

- What makes this particularly useful
- Tips for getting the most out of it

## Related Links

- [Relevant link 1](https://example.com)
- [Relevant link 2](https://example.com)
```

### Step 3: Update the README

Add a row to the relevant category table in [README.md](README.md). If your use case doesn't fit an existing category, suggest a new one.

### Step 4: Open a PR

Submit your pull request with a brief description of the use case and why it's valuable.

---

## Guidelines

- **One use case per markdown file**
- **Only submit use cases you have actually tested and verified** — we value real, working automations
- Keep descriptions concise but detailed enough for someone to replicate
- Include actual prompts/configurations that work
- Duplicates are fine if the approach is meaningfully different
- **No crypto trading bots** — monitoring and tracking use cases are acceptable

## What We're Looking For

✅ Real automations you've run for at least a day
✅ Clear, replicable instructions
✅ Practical use cases that make life genuinely better
✅ New categories that serve underrepresented audiences

## What We Don't Accept

❌ Theoretical or untested use cases
❌ Crypto trading bots or financial manipulation tools
❌ Use cases that require security anti-patterns (root access, hardcoded keys)
❌ Spam or promotional content

## Questions?

Open an issue or reach out to [Mohit Chaprana on LinkedIn](https://linkedin.com/in/ammohitchaprana).
