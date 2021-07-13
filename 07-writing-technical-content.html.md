---
title: Writing Technical Content
layout: article
---

At strongDM, technical content appears primarily in our [technical documentation](https://strongdm.com/docs). This section will lay out the guiding principles of technical content, discuss the main types of technical content, and outline the process of writing and editing technical articles.

## Basics

Someone reading technical content is usually looking to answer a specific question. That question might be broad in scope or it might be narrowly focused, but either way our goal is to provide answers without distraction.

For each project, consider your audience's background, goal, and current mood. Ask these questions:

- Is the reader a prospective user, a new user, or an experienced user?
- What is the goal of the user? To complete a task? To research a topic?
- Is the user in the middle of a task? Are they in a hurry? Could they be frustrated?

We do not want to overload our audience with unnecessary information, choices, or complex ideas or phrases when we do not have to. This is particularly critical when a user may be new and/or frustrated. 

When relevant, provide a brief outline of an article's focus in an introductory paragraph or section, and stick to the topic at hand. Keep sentences, paragraphs, and procedural steps focused and concise. Provide prerequisites, if necessary, to ensure that the reader is aware of what foreknowledge, software, accounts, access, or other items they may need before they waste their time reading a guide they cannot complete.

## Types of technical content

Technical content articles vary in target audience, goal, and tone depending on the task at hand and the anticipated audience for the articles.

## Guidelines

### Writing technical content

When writing technical content, follow the style points outlined in the [Voice and tone](/02-voice-and-tone.html.md) and [Grammar and mechanics](/04-grammar-and-mechanics.html.md) sections. Additionally, here are some more specific pointers for writing technical content.

#### Stay relevant to the title

When a user clicks the title of an article, they expect to find inside the article more information that directly pertains to the title they clicked on. Do not stray too far from the title or topic at hand. Use links to make related content available. If you find you are getting too far from the intended topic, then you may need to create a separate but related article.

#### Keep headlines and paragraphs short and scannable

Focused users often scan an article for the part that will answer their particular question. Be sure headings are short, descriptive, and parallel, to facilitate scanning.

#### Use second person and describe actions to a user

Technical content talks to users when support agents cannot. Address the user, rather than speaking about some hypothetical third party who uses the product.

#### Strive for simplicity and clarity

Be as clear as possible. Use simple words and phrases, avoid gerunds and hard-to-translate idioms or words, focus on the specific task, limit the number of sentences per paragraph. If you must include edge cases or tangentially related information, set it aside in a note or a similar element.

#### Provide context through embedded screenshots, videos, and GIFs

Screenshots, videos, and GIFs may not be necessary for every article or process, but they can be helpful to orient new users. Crop screenshots tightly around the action to focus attention. Follow image contribution rules. Ensure that images are necessary and helpful to convey a point, not superfluous and cluttered.

#### Be specific about the sections or steps that you reference

When possible, avoid referencing an aforementioned step or section of the page with “above.” Instead, note the part of the page you are describing, or cross-reference it with a link to the section.

For example, change “Edit the authorized keys file for the user specified above” to “Edit the authorized keys file for the user specified during server setup.”

### Formatting technical content

Technical content uses organization, capitalization, and other formatting to help convey meaning. Although articles are organized differently, some formatting tips are consistent throughout all technical content.

#### Headings

Organize article content with H2s and H3s. Use H2s for higher-level topics or goals, and use H3s within each section for supporting information or tasks.

* Use sentence case for all headings other than H1 titles. Avoid the use of gerunds when starting headings where possible. As previously stated, you should be addressing the user. "Creating a gateway" is ambiguous. "Create a gateway" is an action, an instruction, and is addressed to the user.
* Refrain from the use of symbols (code markers, carets, brackets) in headings, and where possible, refrain from the use of any punctuation markings at all.

#### Ordered Lists

Only use ordered lists for step-by-step instructions. Separate steps into logical chunks, with no more than two related actions per step. When additional explanation or a screenshot is necessary, use a line break inside the list item. The line items should each follow on the subsequent line, and not have extraneous new lines between them. Ordered lists, in Markdown, should use the 1. 1. 1. formatting so that the numbers are generated on build.

#### Unordered Lists

Use unordered lists to display examples or multiple notes. If an unordered list comprises more than 10 items, use a table instead. The line items should each follow on the subsequent line, and not have extraneous new lines between them.

#### Cross References

When cross-referencing another page from strongDM documentation, link to the page and use the actual page title or section header name in the link. Links are not underlined or italicized.

- Please read the [Connection to SQL Datasources](https://www.strongdm.com/docs/user-guide/connect-to-resources/connection-sql-datasources) guide for specific SQL connection requirements.
- See section **Database Overrides**.

When cross-referencing a non-strongDM page, such as documentation or a technical spec from another company, link to the page and be as descriptive as possible in and around the link so that the reader knows they will be directed away from strongDM. Use the other company’s name and the page title or section.

- You can read more about [AWS KMS](https://docs.aws.amazon.com/kms/latest/cryptographic-details/intro.html) in Amazon’s documentation.

#### Images
Images should be saved as PNG. There is no default size, but make sure to run images through tinypng.com before uploading them, so that your images are not gigantic.

Image captions should describe what is shown in one sentence or less (fragments are OK), and they should end with a period if the captions are complete sentences.

If captions are fragments, there should be no ending punctuation, and title case should be used.

- Add Gateway
- Secret Stores Settings
- TablePlus Client
- Configure Identifiers

In image captions, button names, property/field names, and website section names are shown in quotes.

- Azure "Register an application" Settings

#### Web Elements

In running text, button names, property/field names, and website section names are bold.

- Click **Network & Internet**.
- Open the **Proxy** tab.
- Turn on **Use setup script**.
- Click the **Advanced** button.
- In the app’s **Authentication** section, select **Add a platform**.



