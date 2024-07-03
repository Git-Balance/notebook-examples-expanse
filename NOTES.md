## Progress

| Directory | Progress |
| --- | --- |
| Hello_World | ran local |

## .gitignore

[.gitignore.io](https://www.toptal.com/developers/gitignore/) was used to help create a .gitingore file

The .gitingore file will:
- Ignore .ipynb_checkpoint directories and their contents

## README.md Files

Every directory has its own README.md file to explain what the files in the directory are meant to do

While there are some exceptions, the README.md files seem to follow a template that is similar to the [README.md file in Hello_World](./Hello_World/README.md). This template has a problem at the start. For example, look at the original start of the [README.md file in Notebook_Dev_Basics](https://github.com/Git-Balance/notebook-examples-expanse/blob/changes/Notebook_Dev_Basics/README.md)
```markdown
# SDSC Expanse Notebook: Notebook_Dev_Basics
This README file provides instructions for running notebooks related to LaTeX and Markdown on Expanse. 
These notebooks contain essential knowledge for developing your own Jupyter Notebooks. 
• LaTeX is a useful tool for math formatting, supported with the notebooks.
• Markdown allows you to add formatted text in the notebooks.\
  **Listof Content**
- [Import Module](#import-module)
- [Launch Galyleo](#launch-galyleo)
- [Environment Modules](#environment-modules)
- [Install Modules](#install-modules)
- [Location](#location)
- [Sources](#sources)
```
This has a few issues. The first issue is specific to this README.md, the unicode character `•` was used to create a list instead of the Markdown standard `-`. This means the README.md file will not render properly on sites like GitHub. The second issue, which is in most README.md files and is likely an issue with the original template for the files, is about the List of Content. It has a few issues issues:
1. Instead of having an empty line between the List of Content, which is what is supposed to be done in Markdown files and the paragraph above it, a `\` is used
2. There is a spelling error. Instead of "List of Content," it is "Lis*to*ve Content"
3. "Listof Content" is indented. This doesn't actually show up in rendered Markdown, but it makes the raw Markdown file more confusing\
