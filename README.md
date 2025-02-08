# TOO EASY - GitHub Contribution Art 🎨

## Introduction
This project is an experiment in **GitHub contribution heatmap art**. The goal is to manipulate commit timestamps strategically to spell **"TOO EASY"** in green squares on the GitHub contributions graph.

Inspired by the idea that coding should sometimes feel "too easy," this script automates the process of creating commits on specific days to form text-based patterns in your GitHub activity history.

## How It Works
The script:
- **Defines a pixel-based pattern** for "TOO EASY" on a 7x50 grid (weeks x days).
- **Commits strategically** on specific days over the past year.
- **Uses `GIT_AUTHOR_DATE` and `GIT_COMMITTER_DATE`** to control commit timestamps.
- **Pushes to GitHub**, allowing the pattern to be rendered on the contribution heatmap.

