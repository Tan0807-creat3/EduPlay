## How to contribute

We welcome anyone who wants to contribute to **EduPlay-Studio**.  
Every contribution matters — from answering questions, reporting bugs, improving documentation, to writing code or designing user experiences.

EduPlay-Studio is an open-source, non-profit educational project. The goal is not speed or hype, but **clarity, learning value, and long-term sustainability**. Contributions should respect that spirit.

Project repository:  
https://github.com/Tan0807-creat3/EduPlay-Studio

Issues tracker:  
https://github.com/Tan0807-creat3/EduPlay-Studio/issues

Pull requests:  
https://github.com/Tan0807-creat3/EduPlay-Studio/pulls


### Contribute as a Community Member

You can contribute without writing a single line of code.

- Answer questions and discussions in the issue tracker  
  https://github.com/Tan0807-creat3/EduPlay-Studio/issues

- Help clarify unclear issues by asking follow-up questions
- Confirm bugs by testing them on your machine
- Suggest better explanations, naming, or user flows
- Provide feedback from a learner’s perspective

Clear communication is as valuable as clean code.


### Contribute as a Developer

If you want to contribute code, start small and focused.

- Look for issues labeled **good first issue**  
  [View issues](https://github.com/Tan0807-creat3/EduPlay-Studio/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22)

- Look for issues labeled **help wanted**  
  [View issues](https://github.com/Tan0807-creat3/EduPlay-Studio/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22)

- Look for issues labeled **bug** if you want immediate impact  
  [View issues](https://github.com/Tan0807-creat3/EduPlay-Studio/issues?q=is%3Aissue+is%3Aopen+label%3Abug)

- Look for issues labeled **enhancement** for higher-impact contributions  
  [View issues](https://github.com/Tan0807-creat3/EduPlay-Studio/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement)

All development work should:
- Be tied to an issue (existing or newly created)
- Be educational in nature
- Prefer readability over cleverness
- Avoid unnecessary dependencies

To contribute code:
1. Fork the repository
2. Create a branch from the relevant issue
3. Make your changes
4. Open a Pull Request with a clear explanation


## Branch Naming Convention

We follow clear and predictable branch naming to keep collaboration smooth.

Branch names should be **short, readable, and meaningful**.


### Regular Git Branches

These branches are long-lived and stable.

- **main / master**  
  The production-ready branch.  
  This branch must always remain stable.  
  Changes are merged here only after review and testing.

- **dev**  
  The main development branch.  
  All features, fixes, and improvements are merged here first.

- **test**  
  The branch used for testing features before they are merged into main.


### Temporary Git Branches

Temporary branches are short-lived and deleted after use.

- **feature/**  
  Used to add, modify, or remove a feature.  
  Example: `feature/interactive-math-quiz`

- **bugfix/**  
  Used to fix non-critical bugs.  
  Example: `bugfix/score-calculation`

- **hotfix/**  
  Used for urgent fixes that must be applied immediately.

- **docs/**  
  Used for documentation-only changes.  
  Example: `docs/setup-guide`

- **experimental/**  
  Used for testing new ideas that may not be merged.

- **wip/**  
  Used for work-in-progress branches that are not ready for review.

- **merging/**  
  Used temporarily to resolve merge conflicts.


### Branch Naming Best Practices

We follow general best practices:

1. Use separators such as `/` or `-`  
   Example: `feature/user-progress-tracking`

2. Start with a category word  
   Common categories:
   - `feature`
   - `bugfix`
   - `hotfix`
   - `docs`
   - `test`
   - `wip`

3. Avoid names with numbers only  
   Bad: `123`  
   Good: `bugfix/issue-123-crash`

4. Avoid very long branch names  
   Be descriptive but concise.

5. Be consistent across the project


## Conventional Commits

We follow **Conventional Commits** to keep commit history clear and meaningful.

Specification:  
https://www.conventionalcommits.org/

Common commit types:

- **feat:** introduces a new feature
- **fix:** fixes a bug
- **docs:** documentation changes
- **style:** formatting, no logic change
- **refactor:** code restructuring
- **perf:** performance improvements
- **test:** adding or fixing tests
- **chore:** maintenance tasks
- **ci:** CI/CD related changes
- **build:** build system or dependencies

Breaking changes must include:
- `!` after the type, or
- a footer starting with `BREAKING CHANGE:`

Commit messages must be written in **lowercase**.

Examples:
- ✅ `feat(game): add interactive quiz mode`
- ✅ `fix(ui): prevent button overlap on small screens`
- ❌ `Feat: Add New Feature`
- ❌ `Fix: Crash Bug`


## Coding Style

Coding style should prioritize:
- readability
- simplicity
- educational clarity

General rules:
- Use meaningful variable and function names
- Avoid deeply nested logic
- Comment non-obvious behavior
- Prefer explicit logic over clever shortcuts
- Keep files and functions reasonably small

If the project uses multiple modules or languages, follow the style already used in that module.

Remember:  
This repository is not only software — it is also a **learning resource**.


## Final Notes

EduPlay-Studio grows through shared effort.

If you are new to open source — this is a safe place to start.  
If you are experienced — your guidance is valuable.  
If you care about education — your contribution matters.

Thank you for helping build EduPlay-Studio.
