## Development Goals

<div>
<img align=right width="50%" src="roadmapillustration2.webp" alt="oveture_devs"/>
</div>

The following is a non-exhaustive, alphabetized list of Overture development
goals. If you have an idea that is not listed below, we encourage you to [submit
a feature request]().

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
| **Song base schema model**    | Remove some of the cancer-specific constraints in our Song's base schema model to support additional datatypes natively.                                                                                                                                                                              |

## How to Contribute

We appreciate your interest in contributing to Overture! Please take the time to
read and follow these guidelines before submitting your contributions.

### Issues and Feature Requests

Before opening a new issue or feature request, please check if a similar one
already exists. If so, please add a comment to the existing issue instead of
creating a new one. When submitting an issue or feature request, please include
a detailed description of the problem or feature you would like to see, along
with any relevant code, error messages, or screenshots. This will help us better
understand the issue and respond more efficiently.

### Pull Requests

We welcome and encourage pull requests from the community. To submit a pull
request, please follow these steps:

1. **Fork the Repository**: Fork the score repository on GitHub.
2. **Clone Your Fork**: Clone your forked repository to your local machine.
3. **Create a New Branch**: Create a new branch for your changes.
4. **Make Your Changes**: Implement your changes and commit them to your branch.
5. **Push Your Changes**: Push your changes to your forked repository.
6. **Submit a Pull Request**: Open a pull request against the main repository.

Please ensure your code adheres to the following guidelines before submission:

- The code should be well-documented and readable.
- The code should be tested.
- Include a clear description of the changes made and the reason for the changes
  in the pull request.
- If contributing to any of the features on our development roadmap, please
  label your pull appropriately

We use GitHub issues and pull requests for communication-related to code
changes. For general discussion, feel free to join our
[Slack channel](http://slack.overture.bio/).

By participating in this project, you are expected to abide by the
[Code of Conduct](https://github.com/overture-stack/SCORE/blob/readme-update/code_of_conduct.md).

Thank you for contributing to Overture-Stack!

