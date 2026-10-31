# .github/workflows

**Who works here:** Each id owns its own ci-<id>.yml. java1 owns gate.yml.

**What goes here:** One workflow file per id (ci-java1.yml, ci-java2.yml, ci-ml1.yml, ci-ml2.yml, ci-ml3.yml), each path-filtered to that owner folders, plus gate.yml which always runs and is the only required check.

**What does not go here:** Another person workflow, or scripts that belong in scripts/.

**Rule:** edit only the folders you own. If you need a change in someone else folder, message the owner or open an issue.
