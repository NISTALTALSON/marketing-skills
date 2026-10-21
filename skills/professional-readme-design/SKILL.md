---
name: professional-readme-design
description: Create polished, modern GitHub README landing pages for skill libraries and developer tools, with verified repository-aware content, animated visual hierarchy, setup instructions, usage examples, and contribution guidance.
---

# Professional README Design

Use this skill when a repository needs a professional, modern README rather than a plain project description. The README should explain what the project is, why it matters, what it includes, how to use it, and how others can contribute.

## Core principles

- Inspect the repository before writing. Derive categories, paths, examples, and counts from real files.
- Present the project professionally. Do not mention private desktop paths, internal collection history, temporary staging names, or personal ownership unless explicitly requested.
- Make claims verifiable. Never invent skill counts, compatibility, licenses, features, or test status.
- Prefer concise, high-signal writing over filler. Use headings, tables, code blocks, and links to make the page scannable.
- Use relative links for repository files and folders whenever possible.
- Keep Markdown valid on GitHub. Test links, code fences, image syntax, and Mermaid syntax where supported.
- Preserve existing project branding and do not rewrite unrelated files.

## Recommended README structure

1. **Hero**
   - Centered animated Capsule Render banner or a repository-local image.
   - Project title, one-line value proposition, and optional navigation links.
   - Use Shields.io badges only when their labels are accurate.

2. **What this is**
   - Explain the project in two or three focused paragraphs.
   - State the intended users and the problem it solves.

3. **What is included**
   - Inspect the actual directory tree.
   - Group contents into useful categories.
   - Use a table with category names, relative paths, and practical outcomes.
   - Avoid exposing source provenance or internal folder labels unless they are part of the public product.

4. **Quick start**
   - Provide clone/install/copy commands that match the repository.
   - Include a single-skill setup for users who do not want the entire collection.

5. **Usage**
   - Show realistic prompts.
   - If the runtime supports it, include both `@skill:name` and slash-command forms.
   - Explain how to provide context: product, audience, goal, constraints, evidence, and desired output.

6. **Workflow**
   - Show how related skills can be chained.
   - A Mermaid flowchart is useful when it clarifies a repeatable process.

7. **Compatibility and structure**
   - Explain the supported Agent Skills layout and show the expected `SKILL.md` structure.
   - Mention runtime differences honestly; do not promise automatic discovery unless verified.

8. **Responsible use**
   - For marketing projects, require truthful claims, privacy-aware targeting, and human review.
   - Explicitly discourage spam, deception, impersonation, and unlawful profiling.

9. **Contributing and license**
   - Explain what makes a useful contribution.
   - Link to the real license file or state that each included component may have its own terms.

## Visual style

Use a restrained, polished visual system:

```markdown
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=230&section=header&text=PROJECT%20NAME&fontSize=58&fontColor=ffffff&animation=fadeIn" alt="Project Name" width="100%" />
  <img src="https://img.shields.io/badge/focus-descriptor-8B5CF6?style=for-the-badge" alt="Focus" />
</div>
```

Use at most a few badges. Keep decorative elements subordinate to the content. Add anchor links for high-value sections such as Explore, Quick Start, Usage, and Contributing.

## Usage examples

Prefer concrete examples over generic instructions:

```text
@skill:content-strategy Build a 30-day content system for a developer tool.
```

```text
/skill seo Audit this landing page and return prioritized fixes with implementation examples.
```

For advanced examples, demonstrate deliberate chaining:

```text
1. Use the positioning skill to define the audience and differentiation.
2. Use the copywriting skill to turn the positioning into page and email copy.
3. Use the launch skill to create a channel plan with milestones.
4. Use the analytics skill to define success metrics and feedback loops.
```

## Validation checklist

Before committing the README, verify:

- The title and value proposition match the repository.
- Every linked path exists.
- Every listed category is represented in the repository.
- Counts and compatibility claims are evidence-based.
- Install commands use the correct directory names.
- Code fences close correctly and language tags are appropriate.
- Badge and image alt text is present.
- No private paths, staging labels, or unrequested source history are exposed.
- Usage examples match the supported activation syntax or are clearly labeled as illustrative.
- License and attribution language matches the actual repository contents.
- Only the intended README or documentation files changed.

## Output contract

Return a complete README that is ready to publish. It should feel like a product landing page for the repository: clear in the first screen, useful in the middle, and trustworthy at the bottom.