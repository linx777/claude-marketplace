# Claude Code Marketplace

A marketplace for Claude Code skills and plugins that can be easily installed and shared.

## Available Skills

### Review Plugin
A sample skill that provides code review capabilities.
- **Location**: `plugins/review-plugin`
- **Description**: Automated code review with best practices checking

## Installation

To install a skill from this marketplace, use the Claude Code marketplace commands:

```bash
# Clone the marketplace repository
git clone <your-github-url> claude-marketplace
cd claude-marketplace

# Install a specific skill
# Copy the skill to your Claude plugins directory
cp -r plugins/review-plugin ~/.claude/plugins/
```

## Creating Your Own Skills

1. Create a new directory under `plugins/`
2. Add a `.claude-plugin/` directory with metadata
3. Add your skill implementation (commands, prompts, etc.)
4. Submit a pull request to add your skill to the marketplace

## Structure

```
my-marketplace/
├── .claude-plugin/           # Marketplace metadata
│   └── manifest.json
├── plugins/                  # All available skills
│   └── review-plugin/        # Sample skill
│       ├── .claude-plugin/   # Skill metadata
│       │   └── plugin.json
│       └── commands/         # Skill commands
├── README.md
└── INSTALL.md
```

## Contributing

Contributions are welcome! Please submit a pull request with your new skill.
