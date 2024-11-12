GitHub Workflow that will run on the `main` branch and on all the branches that are called `pr/*`

This allows the developers to use any branch-name to either avoiding running the CI jobs (and incurring costs or hitting the parallel limitations)
or to pick a branch name called `pr/SOMETHING` and making the CI job run.

This might be interesting if you want to reduce the use of the CI in your oranization, but would like to make it easy
for contributors to turn on GitHub Actions in their forks.

So in-house developers would use any branchname except ones starting with `pr/` and contirbutors could use a branch name like `pr/SOMETHING`.

