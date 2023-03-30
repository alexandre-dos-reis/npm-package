# Publish npm package with changesets

A test using changesets to publish npm package.

## Setup with `pnpm`

### Create a git project

- Create a folder `mkdir name-of-your-project`
- Initialize a git repo `git init`

### Github permission

- On the repository, go to `Settings` > `Actions` > `Generals` > `Workflow permissions`
  - Choose: `Read and write permission`
  - Enable: `Allow Github Actions to create and approve pull requests`

## Resources

- https://github.com/changesets/changesets
- https://github.com/changesets/action
- https://github.com/christian-hackyourshack/npm/tree/main/packages