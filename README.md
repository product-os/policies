# approval-policy

Source of truth for [policy-bot](https://github.com/palantir/policy-bot) configuration for the balena organization.

> `policy-bot` is a [GitHub App](https://developer.github.com/apps/) for enforcing
approval policies on pull requests. It does this by creating a status check,
which can be configured as a [required status check][].
>
> While GitHub natively supports [required reviews][], `policy-bot` provides more
complex approval features:
>
> - Require reviews from specific users, organizations, or teams
> - Apply rules based on the files, authors, or branches involved in a pull request
> - Combine multiple approval rules with `and` and `or` conditions
> - Automatically approve pull requests that meet specific conditions
