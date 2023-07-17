# Contributing to REST API

## How to contribute

We use [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow), so all code changes happen through pull requests

### Create a new issue for the feature/fix you want to be worked on

1. Give the issue a short and precise name.
2. Include a short description, a list of tasks and optionally screenshots, code blocks or steps to reproduce (in the case of a bugfix).
3. Add any relevant labels (documentation, bug, etc).
4. Submit the issue. It will now be visible in the `Todo` column on our corresponding project board.

### When you're ready to work on an issue

1. Assign yourself to the issue and move it to the `In Progress` column on the project board.
2. You can then **create a new branch** on the issue page. The name should follow the format `[tag]/[issue number]-[issue name]`. Eg. `feat/13-login-page`.
3. **Create a draft pull request** from that branch into the `dev` branch. There you can add additional information through comments and other developers can see your progression.
4. You can now start pushing to your new branch. All commits should follow the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) format.

### When the issue is solved

1. Make sure all checks have passed. If the continous integration (CI) check has failed, you can click on it to see which step. If it's a formatting issue run `pnpm format` and push. If any other steps fail, read the error and fix accordingly.
2. Mark the pull request as ready for review and assign one or more reviewers.
3. The reviewer will approve or request more changes.
4. If the pull request is approved the branch can be merged and the issue will be closed automatically.

## Write bug reports with detail, background, and sample code

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
- Be specific!
- Give sample code if you can.
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

## Use a Consistent Coding Style

- If you're using vscode, make sure to use the [prettier vscode extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- You can run `pnpm format` to format all files according to our preference
