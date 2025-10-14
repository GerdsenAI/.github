# GerdsenAI Organization README Setup

This repository contains the automated README setup for the GerdsenAI GitHub organization profile.

## Structure

- **README.md** - The main README that displays on the organization profile (auto-generated)
- **README.gtpl** - Template file used to generate README.md with dynamic content
- **.github/workflows/markscribe.yml** - GitHub Actions workflow that updates README.md daily

## How It Works

The GitHub Actions workflow runs:
1. **Weekly** on Sundays at midnight (UTC)
2. **On push** to the main branch
3. **Manually** via workflow_dispatch

The workflow uses [readme-scribe](https://github.com/muesli/readme-scribe) to populate the template with:
- Recent repository contributions
- Latest projects
- Recent pull requests
- Recently starred repositories

## Customization

To customize the README:
1. Edit `README.gtpl` with your desired content
2. Commit and push to the main branch
3. The workflow will automatically regenerate `README.md`

## Contact Information

- **Website:** https://gerdsen.ai
- **Email:** info@gerdsen.ai

## Features

✅ Professional dual-theme compatible emojis  
✅ Clean, minimal design  
✅ Automated weekly updates  
✅ GitHub Actions integration  
✅ No external social media links  
✅ Profile statistics include private repositories  
