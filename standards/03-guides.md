# Creating Guides

## Overview Section

### Purpose & Prerequisites

**This guide is for** [target audience] who need to [primary goal/task]. By the end of this guide you will [specific learning outcomes/deliverables].

**You will need:**
- [Required software/tools with versions]
- [Required access/permissions]
- [Required background knowledge]
- [Time estimate if applicable]

### Background Information

[2-3 sentences providing essential context and background information that readers need to understand the guide]

### Visual Overview (Optional)

[If applicable, include a diagram or visual representation of the end goal/architecture]

## Getting Started

Clear step-by-step instructions for an initial prerequisites setup (i.e. Using the Quickstart)

## Structuring of Primary Steps

1. **Introduction:** Provide a brief overview of what this step accomplishes and why it's necessary

2. **Implementation:** Stepwise instructions on what to do.

    :::tip Using Codeblocks

    - Always reference the language being used
    - When appropriate use the following syntax to reference the source: 
        -  `markdown title="website/docs/04-standards/03-guides.md"`


    ```markdown title="website/docs/04-standards/03-guides.md"
    # The title value renders out the code block with the path provided
    ```

    :::

3. **Validation** How can we verify the implementation was successful. What is the expected output? What common errors can occur and what is the relevant solution?

## Best Practices

### Markdown Elements

- The top level heading (ex. # Top Title) will be used by docusaurus for the sidebar label

- Docusaurus supports codeblocks, [tabs](https://docusaurus.io/docs/markdown-features/tabs), [dropdowns](https://docusaurus.io/docs/markdown-features#details) and [admonitions](https://docusaurus.io/docs/markdown-features/admonitions).

    :::tip Using Codeblocks

    - Always reference the language being used
    - When appropriate use the following syntax to reference the source: 
        -  `markdown title="website/docs/04-standards/03-guides.md"`


    ```markdown title="website/docs/04-standards/03-guides.md"
    # The title value renders out the code block with the path provided
    ```
    :::

- Include callouts for important information using these styles:
  
    :::tip
    **Helpful Tips**
    Provide additional insights or shortcuts
    :::

    :::caution
    **Important Notes**
    Highlight crucial considerations or potential pitfalls
    :::

    :::info
    **Additional Context**
    Provide supplementary information that adds value
    :::

- If your page shares the same name as a folder, you can use the DocsCardList component to automatically display card-style links to all files contained within that folder:

    <DocCardList />

- Use dropdowns to condense the page and hide optional or supplemental content

    <details>
    <summary>**Click here for the markdown code used to write the above examples**</summary>

    ``````

    ## Markdown formatting 

    When adding and editing markdown files within the project repository there are a few considerations to be made to ensure your files get rendered correctly by docusaurus:

    - The top level heading (ex. # Top Title) will be used by docusaurus for the sidebar label

    - Docusaurus supports codeblocks, [tabs](https://docusaurus.io/docs/markdown-features/tabs), [dropdowns](https://docusaurus.io/docs/markdown-features#details) and [admonitions](https://docusaurus.io/docs/markdown-features/admonitions).


        :::tip Using Codeblocks

        - Always reference the language being used
        - When appropriate use the following syntax to reference the source: 
            -  `markdown title="website/docs/04-standards/03-guides.md"`


        ```markdown title="website/docs/04-standards/03-guides.md"
        # The title value renders out the code block with the path provided
        ```
        :::

    - Include callouts for important information using these styles:
    
        :::tip
        **Helpful Tips**
        Provide additional insights or shortcuts
        :::

        :::caution
        **Important Notes**
        Highlight crucial considerations or potential pitfalls
        :::

        :::info
        **Additional Context**
        Provide supplementary information that adds value
        :::

    - If your page shares the same name as a folder, you can use the DocsCardList component to automatically display card-style links to all files contained within that folder. This creates a dropdown-style navigation menu.

    <DocsCardList />

    <details>
    <summary>**Click here for the markdown code used for the above examples**</summary>
    [The content seen in this dropdown would go in here]
    </details>

    ``````

    </details>

Add support callouts at key points in your guide, especially before complex procedures, after steps where users commonly encounter issues and when introducing advanced concepts:

    :::info Need Help?
    Having trouble? Connect with us through our [community support channels](/community/support).
    :::

### Writing Style

1. **Voice & Style:** 
    - Use active voice: "Run the command" vs "The command should be run"
    - Start instructions with verbs: "Install the package" vs "The package should be installed"
    - Keep paragraphs focused on one topic.

2. **Structure**
   - Break complex procedures into smaller steps
   - Scaffold concepts appropriately (basic → advanced)
   - Include validation steps when appropriate
   - Provide troubleshooting guidance for complex steps when appropriate
   - Use numbered lists for sequential steps
   - Use bullet points for related but non-sequential items

3. **Include Context**
   - Explain the "why" behind important steps
   - Provide relevant background information
   - Link to related documentation

### Visual Elements
- Use Screenshots When Helpful, keep images current and provide alt text for accessibility

## Quality Checklist

Before publishing, ensure your guide:

- [ ] Clearly states its purpose and audience
- [ ] Lists all prerequisites
- [ ] Includes necessary background information
- [ ] Provides step-by-step instructions
- [ ] Shows example code and expected outputs
- [ ] Includes troubleshooting guidance
- [ ] Has been tested end-to-end
- [ ] Clear headings
- [ ] Uses consistent formatting
- [ ] Proper code highlighting
- [ ] Includes relevant visuals
- [ ] Links to related documentation are valid and relevant

## Wrapping Up

Conclude your guide with a clear call to action:

:::info Next Steps
List specific, actionable next steps, link to related guides or documentation or suggest common use cases to explore
:::