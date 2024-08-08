ads via Carbon
I've spent 2 years learning DNS while building NSLookup.io. Now, I'm teaching everything I know.
ADS VIA CARBON
Advertising sustains the DA. Ads are hidden for members. Join today
On this page
README format
README sections
Project name and introduction
Table of contents (TOC)
Requirements
Recommended modules
Installation
Configuration
Troubleshooting & FAQ
Maintainers
Changes from README.txt
Advanced help module
Sample README
Documenting your project
Help text standards
Module documentation guidelines
Project page template
README Template
Working with Drupal's Help system
Using simplytest.me as a project demo
Help Topic Standards
README.md template
Last updated on 13 March 2024
The Drupal community recommends using the Markdown format to create a README.md file. Please note that the Drupal Coding Standards have not yet been updated to allow Markdown files, conversion should only be undertaken at the request of an existing project maintainer.

For a quick introduction to Markdown, see Markdown Guide's Basic Syntax or GitLab Flavored Markdown (GLFM) for a more comprehensive run-down. Please also review the Drupal Coding Standards for Markdown files prior to making changes.

README documentation can include more Markdown-features than those used in the example snippets in this template. For instance, Markdown let you create hyperlinks that can be clicked when the README.md is rendered in GitLab or by a compatible program (e.g. Advanced Help).

You can generate a boilerplate README.md with the following command: drush generate readme. The generated text does not follow these guidelines exactly, but may serve as a good starting point.

README format
Drupal recommends the following README formatting:

Headings capitalized with an initial capital, following standard English sentence rules
Headings prefixed with #/##/### to indicate level of heading (h1/h2/h3) followed by a blank line
Project name is the first line of the document, and only level one heading (#)
Two lines prior to ##/### headings
No leading or trailing spaces
Bulleted lists denoted by dashes (-)
Ordered lists use "1", for easier updates and to avoid errors (see Configuration)
Nested lists indented with 4 spaces
Links should have a meaningful link text, for example:
[Drupal](https://www.drupal.org/) (i.e. not just the URL)
Text manually word-wrapped within around 80 cols
README sections
Drupal recommends the following README sections:

Project name and introduction (required)
Table of contents (optional)
Requirements (required)
Recommended modules (optional)
Installation (required, unless a separate INSTALL.md is provided)
Configuration (required)
Troubleshooting & FAQ (optional)
Maintainers (optional)
Project name and introduction
Start the README.md with the project name, and an introduction to the project. The project name is the only level one heading in the document. This must be the first line of the document and must be followed by one blank line.

The introduction summarizes the purpose and function of the project, and should be concise (a brief paragraph or two). This introduction may be the same as the first paragraph on the project page.

This section should include a link to the project page and issue queue. If the project is a sandbox, these links should go to the sandbox until promotion.

# Administration Menu

The Administration Menu module displays the entire administrative menu tree
(and most local tasks) in a drop-down menu, providing administrators one- or
two-click access to most pages.

For a full description of the module, visit the
[project page](https://www.drupal.org/project/admin_menu).

Submit bug reports and feature suggestions, or track changes in the
[issue queue](https://www.drupal.org/project/issues/admin_menu).