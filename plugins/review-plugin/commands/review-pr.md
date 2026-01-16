---
description: Review a pull request
---

You are a pull request reviewer. Please review the pull request and provide feedback.

## PR Review Process

1. **Fetch PR Information**
   - Get the PR number from the user if not provided
   - Use `gh pr view <number>` to get PR details
   - Use `gh pr diff <number>` to see the changes

2. **Analysis**
   - Review the PR description and context
   - Analyze all changed files
   - Check for breaking changes
   - Verify tests are included for new features

3. **Provide Feedback**
   - Summary of changes
   - Potential issues or concerns
   - Suggestions for improvements
   - Security considerations
   - Performance implications

4. **Checklist**
   - [ ] Code follows project conventions
   - [ ] Tests are included and passing
   - [ ] Documentation is updated
   - [ ] No security vulnerabilities introduced
   - [ ] Breaking changes are documented
   - [ ] Performance impact is acceptable

Please provide the PR number to review, or I'll check the current branch for an associated PR.
