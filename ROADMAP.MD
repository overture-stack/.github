## Development Goals

<div>
<img align=right width="50%" src="https://raw.githubusercontent.com/overture-stack/.github/master/profile/roadmapillustration2.webp" alt="oveture_devs"/>
</div>

The following is a non-exhaustive, alphabetized list of Overture development
goals. If you have an idea that is not listed below, we encourage you to **[submit
a feature request](https://github.com/overture-stack/roadmap/issues/new?assignees=&labels=&projects=&template=Feature_Requests.md)**.

| Feature                       | Description                                                                                                                                                                                                                                                                                           |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Beacon-based search**       | Add support for a GA4GH Beacon interface to Arranger.                                                                                                                                                                                                                                                  |
| **Chatbot**                   | A new LLM-based chatbot module to perform custom searches and visualizations on our platforms.                                                                                                                                                                                                        |
| **Data Access Portal**        | A GA4GH compliant electronic system for (1) researchers to request data access to controlled-access datasets (2) data access officers to review and act on those requests (3) admins to monitor data access.                                                                                          |
| **Data curator**              | - A new LLM-based module to execute data extraction and harmonization to align existing data to a Lectern schema.                                                                                                                                                     |
| **Data Dictionary Viewer**    | A generalized data dictionary component in Stage that displays schemas in an easy-to-read format from Song.                                                                                                                                                                                           |
| **Federated search**          | An Overture module that supports searching across multiple Overture instances, and includes functionalities such as minimal threshold for cell size of returned aggregated results (for controlled-access data). This provides a visual UI to browse and dynamically drill down/refine query results. |
| **Lyric**                     | A data submission service compatible with any structured data defined in Lectern. This includes generating TSV templates and validating against a Lectern defined JSON schema.                                                                                                                        |
| **Ontology-based search**     | A tree viewer supporting searching across data based on selecting a branch of an ontology tree, e.g., ‘all subclasses of “cancer”’                                                                                                                                                                    |
| **Ontology-based validation** | Update existing Lectern validation to support validation of values against an ontology, e.g., the field “disease” must have a value from the MONDO disease hierarchy.                                                                                                                                 |
| **Participant portal**        | A GA4GH compliant electronic system to support participant enrollment in new studies, collecting their demographic information and data consent, enabling dynamic consent.                                                                                                                            |
| **Phenopacket export**        | Provide a GA4GH Phenopackets formatted export of our data.                                                                                                                                                                                                                                             |
| **Song base schema model**    | Remove some of the cancer-specific constraints in our Song's base schema model to support additional datatypes natively.                                                                                                                                                                             |
## How to Contribute

By participating in this project, you are expected to abide by our [Code of Conduct](/community/code-of-conduct). Please take the time to read it carefully before contributing.

**Getting Started:** Our primary platform for community support, feature requests, and general discussions is GitHub Discussions. This allows us to keep all conversations in one place and make them easily searchable for future reference.

**Community Support:** Our primary platform for community support, feature requests, and general discussions is [GitHub Discussions](https://github.com/overture-stack/docs/discussions). This allows us to keep all conversations in one place and make them easily searchable for future reference.

- **Getting Help:** If you need assistance with Overture, please create a [new discussion in our support category](https://github.com/overture-stack/docs/discussions/categories/support).
  - Before creating a new discussion, please search existing discussions to see if your question has already been answered.
- **Feature Requests & Proposals:** We love hearing your ideas for improving Overture! Before making a feature request, please check our [**feature roadmap**](https://github.com/orgs/overture-stack/projects/11/views/1) to see if your idea is already planned.
  - If your idea isn't on the roadmap, feel free to [**submit a feature request**](https://github.com/overture-stack/docs/discussions/categories/ideas) by creating a new discussion in our Ideas category 
- **Report a Potential Bug:** We use GitHub Issues primarily for tracking confirmed bugs and ticketing development tasks. If you come across a potential bug or issue, please first post it to our [**GitHub support discussion forum**](https://github.com/overture-stack/docs/discussions/categories/support).
  - This allows us to confirm the issue and gather more information if needed. If we determine that further development is required, we will create and tag you into a GitHub Issue from your discussion post.

## Our Development Process

We use GitHub issues and pull requests for communication related to code changes. 

### Branch Organization

We use the following standard branches:

- `main` is for stable production code
- `develop` is the integration branch for new features
- `feature/<name>` for feature branches
- `release/v<version>` for release branches
- `hotfix/<name>` for hotfix branches

## Pull Requests

### Submitting a Pull Request

We welcome and encourage pull requests from the community. To submit a pull request, please follow these steps:

1. **Fork the Repository**: Fork the Overture repository on GitHub.
2. **Clone Your Fork**: Clone your forked repository to your local machine.
3. **Create a New Branch**: Create a new branch for your changes. Use lowercase and hyphens (e.g., `feature/user-authentication`). Include ticket/issue numbers when applicable (e.g., `feature/PROJ-123-user-authentication`).
4. **Make Your Changes**: Implement your changes and commit them to your branch. Write clear, concise commit messages in present tense (e.g., "Add feature" not "Added feature"). Reference issue numbers in commits when applicable.
5. **Push Your Changes**: Push your changes to your forked repository.
6. **Submit a Pull Request**: Open a pull request against the main repository.

### Best Practices

1. **Keep PRs as small as possible:** Focus on one feature or bug fix per pull request. Break large changes into smaller, more manageable pieces making it easier for reviewers to understand and approve your changes.

2. **Use descriptive titles:** Start with a verb (e.g., "Add", "Fix", "Update", "Refactor"), briefly summarize the main purpose of the PR and include the issue number if applicable (e.g., "Fix user authentication bug (#123)").

3. **Describe how you tested it:** Explain the testing process you followed and mention any new automated tests you've added.

4. **Provide a clear description:** Explain the purpose of your changes and list the main modifications you've made. Mention any potential side effects or areas that might need extra attention.

5. **Link related issues:** Reference any related issues or pull requests. Use GitHub keywords to automatically link issues (e.g., "Closes #123", "Fixes #456").
6. **Keep the PR's branch up-to-date:** Regularly rebase your branch on the latest main branch and resolve any merge conflicts promptly.

7. **Respond to feedback:** Be open to suggestions and willing to make changes. Address all comments from reviewers. If you disagree with a suggestion, explain your reasoning politely.

8. **Include documentation updates:** If your changes affect user-facing features, update or create and issue detailing the relevant changes need to the documentation. Where appropriate include inline comments for complex code sections.

10. **Be patient:** Reviewers will likely be unable to respond immediately. However, feel free to follow up politely if you haven't received feedback after a reasonable time.

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
- Use task lists (using `- [ ]` in Markdown) to track completion of sub-tasks
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
