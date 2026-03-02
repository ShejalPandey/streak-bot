# Daily GitHub Streak Bot

This bot automatically commits to your GitHub repository daily to maintain your contribution streak.

## How It Works

1. **Fork or use this repository** as your personal "streak" repo
2. **The GitHub Action runs daily** at midnight UTC
3. **It creates a commit** with a simple timestamp update
4. **GitHub detects the commit** and counts it as a contribution

## Setup

1. Create a new repository (or fork this one)
2. The workflow already exists in `.github/workflows/daily-streak.yml`
3. That's it! The action will run automatically each day

## Customization

Edit `.github/workflows/daily-streak.yml` to customize:
- **Schedule**: Change the cron schedule (default: midnight UTC daily)
- **Commit message**: Modify the commit message format

## Important Notes

- GitHub Actions must be enabled in your repository
- The workflow uses the default GitHub token which has commit permissions
- Your streak will show "1 contribution" each day
