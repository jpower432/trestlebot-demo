# trestlebot-demo-cd
Testing and demonstrating trestlebot in various configurations for editing component definitions

# Example with a default main branch

- Automated notification of a release to downstreams
- Automated pushes to main with updates
- Automated creation of new component definitions

# What is missing

- The develop branch. This example uses GitHub flow to keep it more lightweight.
- Rules CSV support

# Ideas
- An automated dry-run [option](https://github.com/RedHatProductSecurity/trestle-bot/issues/181). It may be generally useful to know if a markdown changes is going to cause assemble to fail before it merged.
- Add markdown generation as part of the `rules-transform` task
- Add markdownlint and yamllint PR [checks](https://github.com/RedHatProductSecurity/trestle-bot/issues/165)
