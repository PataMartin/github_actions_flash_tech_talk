# GitHub Actions Flash Tech Talk

This repository contains the demo for the Patagonian Github Actions Flash Tech
Talk.

## Usage

- The main workflow is stored under .github/workflows/lint-test.yml
- A PR from broken-unittest branch to main will trigger the action and fail on
  the test job.
- A PR from broken-format branch to main will trigger the action and fail on the
  lint job.
- A PR from all-good branch will trigger the action and succeed.
