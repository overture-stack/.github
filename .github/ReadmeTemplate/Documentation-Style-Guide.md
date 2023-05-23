# :book: Documentation Guidelines 

**Estimated Reading Time:** 5 minutes 

---

Thanks for taking an interest in our documentation. This guide outlines principles and best practices for writing clear and consistent Overture documentation. See our contribution guide for information on how to submit changes. Join our slack channel if you have any unanswered questions, comments, or suggestions. We're here and happy to chat.

## Audience

Overture has two primary audiences:

**Software Engineers**: They install, customize and configure Overture components within their software stack.

**Bioinformaticians & Data Scientists**: They use Overtures CLI tools and GUIs to interact with the data.

## Voice & Tone

Our writing should consistently convey a friendly, informative and empathetic personality.

We want to ensure that our documentation gets written in the right tone. Different contexts will necessitate different approaches. Tutorials typically require a more enthusiastic and instructive tone, while warnings require a more serious and pressing tone. To help know if your tone matches the content, ask yourself, "What is the reader likely feeling when presented with this content? Why are they here?" From your answer, adjust your language with the appropriate tone.

## Language & Grammar

Practice best judgment. These are non-prescriptive guidelines, and there will always be exceptions. 

### Language

We use Canadian English (en-CA) as our standard language for all written and verbal communication.

### Use an Active Voice

The active voice is concise and more accessible for readers to comprehend. Active voice is naturally used in conversation and therefore, readers understand and engage more with writing in the active voice.

| 👎 Disengaging| 👍 Engaging|
|---|---|
|The developer environment has been set up successfully.|We have successfully set up the developer environment.|
|The necessary tools and dependencies are being installed.|We are installing the necessary tools and dependencies.|

### Put Conditional Clauses First

Put conditional clauses up front in sentences. With conditional clauses upfront, readers can skim or skip information they do not require. If done consistently, this saves significant time reading irrelevant information.

| 👎 Slow | 👍 Skimmable |
|---|---|
|See How to Use the Score Client for more information | For more information, see How to Use the Score Client.|
| Set the analysis state to published, this will enable the analysis to be indexed| To index the analysis, set the analysis state to published |

### Write Accessibly

Take note of how you describe software behaviours or user actions. Each reader will have a unique background and familiarity with the content, so avoid using language that assumes knowledge.

| 👎 Sets expectations that can lead to frustration| 👍 No assumptions, made reader friendly|
|---|---|
|Start by *simply* entering the following command|Start by entering the following command|
|To *easily* interact with our API see the Song Swagger UI| To interact with our API see the Song Swagger UI|

Whenever possible, also include descriptive links to prerequisite or contextual material. Our services benefit a variety of people and data; therefore, experience levels and fields of expertise can vary significantly from user to user. 

## Formatting & Punctuation

### Markdown

Documentation is written using GitHub-flavoured markdown within `.md` files. For information on basic syntax, see this [ cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) or for more in-depth information, check out the official [Github-flavored Markdown info page](https://docs.github.com/en/get-started/writing-on-github).

If you draft `.md` files within VS code, we have found the following [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles) extension helpful.

### Using Code Blocks

To wrap code within a code block, use ``` before and after the sample code.

For example:

```
Here is a code block
```

When appropriate, include the language immediately following the first ```

Example(s):

```bash
# this is a bash terminal
cd desktop
```

```json
// this is a JSON file

{
  "name": "variant_calling",
  "schema": {
    "type": "object",
    "required": [
      "experiment",
      "donor_clinical_data"
    ]
  }
}
```

### Headers

To appropriately capitalize words in a title or heading, follow these guidelines:

- Capitalize the first word of a title or subtitle, even if it is a little word like "The" or "A."
- Capitalize the first word after a colon and dash (ex., "Self-Report" instead of "Self-report").
- Capitalize words of four letters or more (e.g., "With," "Between," and "From").
- Except for the above rules, lowercase minor words that are three letters or fewer in a title or subtitle.

### Numbered lists vs bulleted points

- **numbered lists** for sequential items
- **bulleted points** for all other lists

### Commas

Use an Oxford comma for a list of three or more items.

| Can lead to confusion | Clearer separatation |
|---|---|
|I had eggs, toast and orange juice for breakfast.|I had eggs, toast, and orange juice for breakfast.|

### UI/Navigation Elements

When referencing UI elements, have them in **Bold**  

1. Click **Documentation** > **Get Started**.
2. Select **Pre-Configuration Setup**.

## Organization

### Modular Documentation 

With modular documentation, we organize our writing into modules, which writers combine into assemblies. Assemblies can include other assemblies. However, modules cannot contain other modules. 

Three types of modules exist:

|Module|Description|
|---|---|
|Concept Module|A concept module is an "understand" module. Concept modules give the user descriptions and explanations needed to understand and use a product.|
|Procedure Module|Procedure modules explain how to do something. A procedure module contains numbered, step-by-step instructions to help the user accomplish a single task.|
|Reference Module|Reference modules provide data that users might want to look up but do not need to remember.|

### User Stories

We combine modules into assemblies that are based on user stories. User stories are specific use cases which a user coming to our documentation may be interested in fulfilling. Modular documentation allows us to reuse modules within various assemblies to fulfill multiple current and future user stories.

Our team is continually documenting user stories. If you have a use case that still needs to be documented, feel free to contact us on our [slack channel](http://slack.overture.bio/) or send us an email at [contact@overture.bio](

For more information on modular documentation, see [Red Hats Modular Documentation Reference Guide](https://redhat-documentation.github.io/modular-docs/)

### Headers

Use level 1 headers at the top of the page and divide your document using the lower level headers for subsections.

Try and use headers wisely, with too many headers it can make the document difficult to navigate. Too little can lead to a disordered page and reduces the readers' ability to scan the document. 

## Images & Diagrams

Images and diagrams can be valuable, but they can take lots of time and require maintenance. When using images or diagrams, consider how beneficial the visualization will be and how frequently you need to update it. 

### Creating Diagrams

We use Mermaid to create our diagrams. For more information, see the official [GitHub Docs on creating Mermaid diagrams](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams).


## Attributions

- Based off the [Pachyderm Documentation Style Guide](https://docs.pachyderm.com/latest/contributing/docs-style-guide/)

- For information on Modular documentation, see [Red Hats Modular Documentation Reference Guide](https://redhat-documentation.github.io/modular-docs/)