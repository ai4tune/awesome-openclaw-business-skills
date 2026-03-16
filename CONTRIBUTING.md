# Contributing

Thanks for improving this repository.

## What To Contribute

- New business workflow skills
- Better input or output examples
- Clearer documentation
- Validation improvements
- Realistic enterprise use cases

## Contribution Rules

1. Keep the positioning focused on business workflows and enterprise AI adoption.
2. Prefer practical, reusable baseline skills over abstract prompt collections.
3. Each skill must include:
   - `README.md`
   - `skill.md`
   - at least one example input
   - at least one example output
4. Explain limitations and intended usage clearly.
5. Do not include private customer data, confidential workflows, or secrets.

## Skill Folder Standard

Each new skill should follow:

```text
skills/<skill-name>/
├── README.md
├── skill.md
└── examples/
    ├── input.md
    └── output.md
```

Recommended sections for each skill README:

- What it does
- Best for
- Input format
- Output format
- Example input
- Example output
- Limitations
- Upgrade ideas
- Related use cases

## Pull Requests

Before opening a pull request:

1. Make sure the new content matches the repository positioning.
2. Run the repository validation workflow locally if you extend it.
3. Keep changes focused and easy to review.
4. Describe the problem, the intended audience, and the expected output quality.

## Issues

Use the issue templates for:

- Skill requests
- Bug reports
- Missing examples
- Documentation gaps

