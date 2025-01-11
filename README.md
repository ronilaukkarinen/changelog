# Life CHANGELOG

The idea for personal changelog is simple: It tracks changes and updates in your life or projects. I got the idea from software projects changelogs that I love to write, they summarize each release changes beautifully.

This changelog uses [semver](https://semver.org/) to categorize changes, headless Obsidian and AI to anonymize data from private to public version via personal-assistant-cli/tasks/update-changelog.sh.

## [Browse CHANGELOG.md](CHANGELOG.md)

## How to set up your own Life CHANGELOG

1. Fork this repository
2. Clone your fork
3. Set up a private CHANGELOG.md file to the root level of your Obsidian vault, or just as plain text to anywhere you want
4. Git clone personal-assistant-cli to the server you want to run it on for automatic updates, set up paths in the script
5. Run the script periodically via cron or other scheduler

## What semver means in Life CHANGELOG

- **Major** version means something big has happened.
- **Minor** version means something larger than usual, but nothing significant has happened. Usually more changes or some step forward.
- **Patch** version means everyday change. This is the most common version, every day life updates.
- Optional or pre-release labels are probably not used in this changelog.

![image](https://github.com/user-attachments/assets/46b6244f-14a1-46cb-bb54-5bb0b7a63449)