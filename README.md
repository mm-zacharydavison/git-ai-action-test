# git-ai-action-test

Test repository for [git-ai-action](https://github.com/mm-zacharydavison/git-ai-action).

## Running Tests

Go to Actions → "Test git-ai-action" → Run workflow

Tests:
- `test-pr-close`: Tests PR close action with specified version
- `test-daily-metrics`: Tests daily metrics action with specified version
- `test-old-version`: Tests that old versions (< v1.0.23) fail gracefully
