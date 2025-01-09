# ambulant-software-catalog

This repository contains the source code for the "Praxis-IT" Quarto book. The book is rendered and deployed to GitHub Pages.

## Viewing the Book

You can view the rendered book online at [Praxis-IT](https://bsenst.github.io/praxis-it).

## Installing Quarto CLI on GitHub Codespaces

To download and install Quarto CLI on a GitHub Codespace, follow these steps:

1. Open a terminal in your GitHub Codespace.
2. Download the `.deb` package using `wget`:
    ```sh
    wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.6.40/quarto-1.6.40-linux-amd64.deb
    ```
3. Install the downloaded package using `dpkg`:
    ```sh
    sudo dpkg -i quarto-1.6.40-linux-amd64.deb
    ```
4. Verify the installation by checking the Quarto version:
    ```sh
    quarto --version
    ```
5. Install TinyText:
    ```sh
    quarto install tinytex
    ```
