# Documenting Projects

Several documentation standards should be met at the level of the organization or project, as opposed to software repos and inline code.

- The following organization documents, templates, and community health files should be included within a dedicated `.github` repository of the organization. 
- This special repository acts as a centralized location for default community health files and templates for the entire organization. Files placed here will apply to all repositories within the organization that don't have their own specific versions of these files.

## .GitHub Repository Structure

Here is an overview of the [Overture-Stack .github repository](https://github.com/overture-stack/.github):

```
.
├── ISSUE_TEMPLATE/
│   ├── bug_report.md
│   ├── feature_request.md
│   └── custom_template.md
├── workflows/
├── profile/
├── Standards/
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── CODEOWNERS
├── FUNDING.yml
├── PULL_REQUEST_TEMPLATE.md
├── README.md
└── ROADMAP.md
```

### ISSUE_TEMPLATE/

This directory contains templates for creating new issues in the repository. It helps standardize the information provided when reporting bugs, requesting features, or submitting other types of issues.

[View ISSUE_TEMPLATE Directory](https://github.com/overture-stack/.github/tree/master/.github/ISSUE_TEMPLATE)

### workflows/

The workflows directory typically contains GitHub Actions workflow files. These YAML files define automated processes for CI/CD, testing, or other repository management tasks.

[View Workflows Directory](https://github.com/overture-stack/.github/tree/master/.github/workflows)

### profile/

This directory is used to customize the organization's GitHub profile. It often contains a README.md file that is displayed on the organization's master page.

[View Profile Directory](https://github.com/overture-stack/.github/tree/master/profile)

### Standards/

This directory likely contains documents outlining coding standards, best practices, and other guidelines specific to the Overture-Stack organization.

[View Standards Directory](https://github.com/overture-stack/.github/tree/master/Standards)

### CODE_OF_CONDUCT.md

This file outlines the expected behavior and values for all contributors and participants in the project, fostering a positive and inclusive community.

[View Code of Conduct](https://github.com/overture-stack/.github/blob/master/CODE_OF_CONDUCT.md)

### CONTRIBUTING.md

The CONTRIBUTING.md file provides guidelines for how to contribute to the project, including information on submitting pull requests, reporting issues, and coding standards.

[View Contributing Guidelines](https://github.com/overture-stack/.github/blob/master/CONTRIBUTING.md)

### CODEOWNERS

This file defines individuals or teams responsible for code in the repository. It's used to automatically request reviews from the relevant people when a pull request changes certain files.

[View CODEOWNERS File](https://github.com/overture-stack/.github/blob/master/CODEOWNERS)

### FUNDING.yml

The FUNDING.yml file is used to provide information about how people can financially support the project, such as through GitHub Sponsors or other platforms.

[View Funding Information](https://github.com/overture-stack/.github/blob/master/FUNDING.yml)

### PULL_REQUEST_TEMPLATE.md

This template is automatically loaded when creating a new pull request, guiding contributors to provide necessary information about their changes.

[View PR Template](https://github.com/overture-stack/.github/blob/master/PULL_REQUEST_TEMPLATE.md)

### README.md

The master README file for the .github repository, likely containing an overview of its purpose and contents.

[View README](https://github.com/overture-stack/.github/blob/master/README.md)

### ROADMAP.md

This file outlines the future plans and direction for the project or organization, helping contributors understand long-term goals and upcoming features.

[View Roadmap](https://github.com/overture-stack/.github/blob/master/ROADMAP.md)