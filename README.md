# SyncAwesomePrompts

This repository automatically syncs GitHub Copilot customizations from the [Awesome GitHub Copilot Customizations](https://github.com/github/awesome-copilot) repository.

## Synced Folders

The following folders are synchronized daily at midnight UTC:

- **chatmodes/** - Chat mode customizations for GitHub Copilot
- **instructions/** - Instruction files for various frameworks and technologies  
- **prompts/** - Reusable prompt templates

## Automation

This repository uses GitHub Actions to automatically sync content every day. The workflow:

1. Runs daily at midnight UTC
2. Can also be triggered manually via workflow dispatch
3. Fetches the latest content from the source repository
4. Updates the three folders with fresh content
5. Commits and pushes changes only if there are updates

Source: https://github.com/github/awesome-copilot
