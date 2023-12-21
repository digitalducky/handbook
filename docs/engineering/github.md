# GitHub

## General Guidelines

- **Always** use **pull requests**.
  - Never commit directly to `main`.
  - `main` branch should be protected on all repos.
- Test locally and ensure CI is passing before merging.
- Use `CODEOWNERS` appropriately to request reviews from the correct teams/people.
- In general, create an **issue** before writing any code. This allows you to have a discussion with the team to ensure the approach you want to take is correct. A pull request without a linked issue is often a red flag 🚩.
  - Exception: Depending on the project, it may be OK to skip creating an issue for `docs` and certain `chore` type commits.
  - Also note that you can link multiple PRs to a single issue if it needs to be broken into multiple steps/tasks.

## Labels

### Standard Labels Used Across All Projects

- `BREAKING-CHANGE`

#### needs

- `needs/docs`
- `needs/tests`
- `needs/triage`

#### size

- `size/xs`
- `size/s`
- `size m`
- `size/l`
- `size/xl`

#### type

- `type/bug`
- `type/chore`
- `type/docs`
- `type/feat`
- `type/fix`

## Projects

We use [GitHub Projects and GitHub Issues](https://github.com/features/issues) for project management.

### Best Practices

In general, add **issues** to project boards and avoid adding **pull requests** to project boards.
Every pull request should have a linked issue.
By only adding issues instead of pull requests, we avoid doubling up entries for the same work on project boards.

If there is no issue linked to a pull request, it may be added to the correct project board, but it is often better to create the relavent issue.