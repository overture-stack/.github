# Contributing to Overture

We appreciate your interest in contributing to the Overture project. Overture-stack is an open source project focusing on the growth and development of reliable genomic data management systems quickly, flexibly, and at multiple scales. We love to see contributions from our community, so please let us know how we can improve or help us by putting up some code that we will help review.

By participating in this project, you are expected to abide by our [Code of Conduct](https://github.com/overture-stack/.github/blob/master/CODE_OF_CONDUCT.md). Please take the time to read it carefully before contributing.

## Communication Channels

- We use GitHub issues and pull requests for communication related to code changes. 
- For general discussion, feel free to join our [Slack channel](http://slack.overture.bio/).
- For detailed information on best practices, see our [standards of practice documentation](https://main--overturedev.netlify.app/docs/Standards/).

## Issues and Feature Requests

Before opening a new issue or feature request, please check if a similar one already exists. If so, please add a comment to the existing issue instead of creating a new one.

### Bug Reports

If you think you have found a bug, we want to know! First, search our issues list on GitHub in case a similar issue has already been opened. If you think you have a new bug, please:

1. Submit a ticket with the `bug` template.
2. Add the label `user-submitted`.
3. Provide a repo with a minimal reproducible setup (if possible).
4. Describe in as much detail, with steps, how to reproduce the bug.
5. Include screenshots or specific commands in the bug report if applicable.
6. Provide as much information as you can (e.g. context, OS, browser). Anything helps when debugging.
7. Provide an example of what you think the expected behavior should be.

The better your bug submission, the faster we will get to fixing it!

### Feature Requests

Have a feature you would love to see? Submit a ticket with the `Feature Request` template which describes the feature you would like to see, why you need it, and how it should work.

- Add the label `user-submitted`.
- Describe in as much detail as you can the feature request.
- Include example usage or why it would be of benefit to users.

When submitting an issue or feature request, please include a detailed description of the problem or feature you would like to see, along with any relevant code, error messages, or screenshots. This will help us better understand the issue and respond more efficiently.

## Pull Requests

We welcome and encourage pull requests from the community. To submit a pull request, please follow these steps:

1. **Fork the Repository**: Fork the Overture repository on GitHub.
2. **Clone Your Fork**: Clone your forked repository to your local machine.
3. **Create a New Branch**: Create a new branch for your changes. Use lowercase and hyphens (e.g., `feature/user-authentication`). Include ticket/issue numbers when applicable (e.g., `feature/PROJ-123-user-authentication`). The following is a list of our standard branches:
   - `main` is for stable production code
   - `develop` is the integration branch for new features
   - `feature/<name>` for feature branches
   - `release/v<version>` for release branches
   - `hotfix/<name>` for hotfix branches 
4. **Make Your Changes**: Implement your changes and commit them to your branch. Write clear, concise commit messages in present tense (e.g., "Add feature" not "Added feature"). Reference issue numbers in commits when applicable.
5. **Run Tests**: Run the test suite to make sure that nothing is broken.
6. **Push Your Changes**: Push your changes to your forked repository.
7. **Submit a Pull Request**: Open a pull request against the `develop` branch of the main repository.

### Creating a Pull Request

- Provide a clear title and detailed description
- Reference related issues
- Include screenshots or GIFs for UI changes
- Assign reviewers and add appropriate labels
- Add [Overture-stack/Reviewers](https://github.com/orgs/overture-stack/teams/reviewers) as a reviewer for your PR

### Using Draft Pull Requests

Draft Pull Requests are an excellent way to document work in progress and facilitate early feedback. Use them to:
- Organize your thoughts and process
- Share early work and ideas with the team
- Get feedback on implementation approaches before finalizing code
- Track progress on long-running features

Guidelines for Draft Pull Requests:
1. **Creation**:
   - Open a pull request and select "Create draft pull request"
   - Clearly mark the title with [WIP] or [DRAFT] prefix
2. **Description**:
   - Outline the current state of the work
   - List planned tasks or improvements
   - Highlight areas where feedback is specifically needed
3. **Updates**:
   - Regularly update the description or provide comments following commits with progress notes
   - Use task lists (- [ ]) to track completion of sub-tasks
4. **Collaboration**:
   - Encourage early feedback and discussion
   - Use the pull request comments for design discussions
5. **Finalization**:
   - Complete all planned work and address feedback
   - Update tests and documentation
   - Click "Ready for review" to move out of draft state

### Merging a Pull Request

- Ensure all CI checks pass
- Obtain the required number of approvals
- Use the project's specified merge strategy (Typically squash and merge)
- Delete the source branch after merging if no longer needed

## Testing Guidelines

1. Test databases via test containers - no in-memory DB or OS-specific services
2. Tests should have no dependencies on any external services (i.e., production micro-service)
3. Tests DO NOT clear their data between runs, meaning that no test should rely on or expect a clean DB when running

Remember to respect our Code of Conduct in all interactions, including ticket submission and pull request conversations.