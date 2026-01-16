# Installation Guide

## Quick Install

### Option 1: Clone and Copy (Recommended)

```bash
# Clone the marketplace
git clone https://github.com/YOUR_USERNAME/claude-marketplace.git
cd claude-marketplace

# Install a specific skill
cp -r plugins/review-plugin ~/.claude/plugins/

# Or install all skills
cp -r plugins/* ~/.claude/plugins/
```

### Option 2: Direct Download

Download the skill you want and copy it to your Claude plugins directory:

```bash
# Create plugins directory if it doesn't exist
mkdir -p ~/.claude/plugins

# Copy the skill
cp -r /path/to/downloaded/skill ~/.claude/plugins/
```

## Verifying Installation

After installation, restart Claude Code or reload your configuration. The skill should now be available as a slash command or skill.

## Uninstalling

To uninstall a skill:

```bash
rm -rf ~/.claude/plugins/review-plugin
```

## Troubleshooting

- **Skill not showing up**: Make sure the skill is in the correct directory (`~/.claude/plugins/`)
- **Permission errors**: Ensure the plugin directory has proper permissions
- **Command not found**: Restart Claude Code after installation
