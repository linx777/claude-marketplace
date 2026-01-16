# Review Plugin

A Claude Code skill that provides automated code review capabilities with best practices checking.

## Features

- Comprehensive code quality analysis
- Best practices verification
- Security vulnerability detection
- Performance optimization suggestions
- Pull request review automation

## Commands

### `/review`
Review code for best practices, bugs, and improvements.

**Usage:**
```
/review
/review src/components/Button.js
/review src/
```

**What it checks:**
- Code quality and duplication
- Best practices adherence
- Performance bottlenecks
- Maintainability issues
- Potential bugs and edge cases

### `/review-pr`
Review a pull request with comprehensive feedback.

**Usage:**
```
/review-pr
/review-pr 123
```

**Review includes:**
- Summary of changes
- Security analysis
- Performance implications
- Test coverage check
- Documentation verification

## Installation

```bash
# From the marketplace root
cp -r plugins/review-plugin ~/.claude/plugins/

# Or directly
git clone https://github.com/linx777/claude-marketplace.git
cp -r claude-marketplace/plugins/review-plugin ~/.claude/plugins/
```

## Configuration

No additional configuration required. The plugin works out of the box.

## Examples

**Review a specific file:**
```
/review src/utils/auth.js
```

**Review current pull request:**
```
/review-pr
```

**Review by PR number:**
```
/review-pr 42
```

## Requirements

- Claude Code
- Git (for PR reviews)
- GitHub CLI (`gh`) for PR review command

## License

MIT
