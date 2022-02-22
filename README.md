# test_ci

## Direct commit to main
When directly committing to main, [this workflow runs](https://app.circleci.com/pipelines/github/Dexterp37/test_ci/4/workflows/9bcccccd-cddb-405f-af6f-954b892a0540/jobs/9). Since the commit message doesn't contain the `[do not deploy]` tag, this is printed: `echo "ERROR - this should never print"`. And that's fine.

## PR with commits with `[do not deploy]`
Will this work? -> **NOPE**

## PR with title  `[do not deploy]` and multiple commits
Will this work?
