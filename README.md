# action-playground

A place to try [dsgraph-action](https://github.com/specsure/dsgraph-action) on a real pull request.

`main` holds the first version of `tokens/tokens.css` and a small app in `app/` whose styles use the tokens. The branch `change-tokens` holds the second: a removed token, a rename, color changes and a dark-theme change. [Pull request #1](https://github.com/specsure/action-playground/pull/1) compares the two: the report is in its comment, with the places in `app/` each change breaks or alters and the styles the pull request adds, and the check fails because the change is breaking and the workflow sets `fail-on: major`. It stays open as the example.
