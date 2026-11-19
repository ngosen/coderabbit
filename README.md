# coderabbit

Organization-wide [CodeRabbit](https://docs.coderabbit.ai/configuration/central-configuration)
settings for the `ngosen` repositories.

`.coderabbit.yaml` here applies to every repository that has no `.coderabbit.yaml` of its own. A
repository that needs more adds its own file with `inheritance: true`, which merges it with this one;
without that line this file is ignored for that repository.

Repository rules are not copied here: CodeRabbit reads each repository's `AGENTS.md` and `CLAUDE.md`
as review guidelines.

Change these settings through a pull request, like any other repository in the organization.
