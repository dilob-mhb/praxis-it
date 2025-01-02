# ambulant-software-catalog

This repository contains a Quarto book project titled "Ambulant Software Catalog". 

## Overview

The Quarto book is structured into multiple chapters, each focusing on different aspects of the software catalog. The main entry point is located in `book/index.qmd`, which provides an introduction and overview of the content.

## Project Structure

- **book/**: Contains the Quarto book files.
  - `index.qmd`: Main entry point of the book.
  - `chapter1.qmd`: Content for the first chapter.
  - `chapter2.qmd`: Content for the second chapter.
  - `_quarto.yml`: Configuration file for the Quarto book.

- **.github/workflows/**: Contains the GitHub Actions workflow for deployment.
  - `deploy.yml`: Automates the deployment of the Quarto book to GitHub Pages.

- **README.md**: Documentation for the project.

- **.gitignore**: Specifies files and directories to be ignored by Git.

## Getting Started

To build and view the Quarto book locally, ensure you have Quarto installed. You can then render the book using the following command:

```
quarto render book
```

For deployment, changes pushed to the main branch will automatically trigger the GitHub Actions workflow to update the GitHub Pages site.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.