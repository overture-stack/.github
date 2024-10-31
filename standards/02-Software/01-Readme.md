# ReadMe

All Overture repositories have a `README.md` file stored in the root directory of the project. 

<details>
  <summary><b>Click here for our templated readme.md</b></summary>
``````
# repoName

What does this component do? Are there any related components (JS client, UI, etc.)? *Keep it to ~3-5 sentences*

</br>

> 
> <div>
> <img align="left" src="ov-logo.png" height="50"/>
> </div>
> 
> *{Component Name} is part of [Overture](https://www.overture.bio/), a collection of open-source software microservices used to create platforms for researchers to organize and share genomics data.*
> 
> 

## Repository Structure

The repository is organized with the following directory structure:

```
.
├── apps/
│   └── server 
└── packages/
    ├── client
    ├── common
    ├── dictionary
    └── validation
```

The modules in the monorepo are organized into two categories:

- __apps/__ - Standalone processes meant to be run. These are published to [ghcr.io](https://ghcr.io) as container images.
- __packages/__ - Reusable packages shared between applications and other packages. Packages are published to [NPM](https://npmjs.com).
- __scripts__ - Utility scripts for use within this repo.


## Documentation

Technical resources for those working with or contributing to the project are available from our official documentation site, the following content can also be read and updated within the `/docs` folder of this repository.

- **[Component Name Overview](link)** 
- [**Setting up the Development Enviornment**](link)
- [**Common Usage Docs**](link)

## Development Environment

- [PNPM](https://pnpm.io/) Project manager
- [Node.js](https://nodejs.org/en) Runtime environment (v20 or higher)
- [VS Code](https://code.visualstudio.com/) As recommended code editor. Plugins recommended: ESLint, Prettier - Code formatter, Mocha Test Explorer, Monorepo Workspace

## Support & Contributions

- For support, feature requests, and bug reports, please see our [Support Guide](https://main--overturedev.netlify.app/community/support).

- For detailed information on how to contribute to this project, please see our [Contributing Guide](https://main--overturedev.netlify.app/docs/contribution).

## Related Software 

The Overture Platform includes the following Overture Components:

</br>

|Software|Description|
|---|---|
|[Score](https://github.com/overture-stack/score/)| Transfer data to and from any cloud-based storage system |
|[Song](https://github.com/overture-stack/song/)| Catalog and manage metadata associated to file data spread across cloud storage systems |
|[Maestro](https://github.com/overture-stack/maestro/)| Organizing your distributed data into a centralized Elasticsearch index |
|[Arranger](https://github.com/overture-stack/arranger/)| A search API with reusable search UI components |
|[Stage](https://github.com/overture-stack/stage)| A React-based front-data portal UI |
|[Lyric](https://github.com/overture-stack/lyric)| A data-agnostic tabular data submission system |
|[Lectern](https://github.com/overture-stack/lectern)| A simple web browser UI that integrates Ego and Arranger |

If you'd like to get started using our platform [check out our quickstart guides](https://main--overturedev.netlify.app/guides/getting-started)

## Funding Acknowledgement

Overture is supported by grant #U24CA253529 from the National Cancer Institute at the US National Institutes of Health, and additional funding from Genome Canada, the Canada Foundation for Innovation, the Canadian Institutes of Health Research, Canarie, and the Ontario Institute for Cancer Research.
``````

</details>

This standardized README template is broken down as follows:

1. **Project Overview**: High-level summary of what the project does, its relationship to the broader Overture platform, and any relevant software components or related projects.

2. **Repository Structure**: An explanation of the repository's structure, using a diagram to illustrate the organization of directories and files (see https://tree.nathanfriend.io/).

3. **Local Development**: Information on development tools, system dependencies, setup instructions, and links to relevant information not suitable for the conciseness of a readme but needed for local development.

4. **Documentation**: Links our more detailed developer docs, platform guides, and other resources to help users understand how to work with and configure the software.

5. **Support & Contribution**: Encourages users to get involved by reporting issues, making contributions, and connecting on our discussion board.

6. **Related Software**: A table about related Overture components and their descriptions.
