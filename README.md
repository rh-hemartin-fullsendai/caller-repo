# caller-repo

Test repo for GitHub Actions `job.workflow_*` context.

Calls a reusable workflow in [shared-workflows](https://github.com/rh-hemartin-fullsendai/shared-workflows).
The reusable workflow uses `job.workflow_repository` and `job.workflow_sha` to
check out its own code and run a co-located script — proving the context points
to the reusable workflow's repo, not this caller.

## Test it

1. Go to Actions → "call-greet" → Run workflow, or
2. Open an issue in this repo.

