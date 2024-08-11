# git2ai

`git2ai` is a Python-based command-line tool that consolidates files in a Git repository into a single text file. This tool is especially useful for generating a comprehensive overview of a project's codebase, including code previews, making it easier to review and analyze code in one place.

## Features

- **File Consolidation:** Automatically traverses the repository directory and consolidates all code files into a single text file.
- **Customizable:** Supports various programming languages and file formats, with the ability to specify custom file extensions.
- **Git Ignore Compatibility:** Honors `.gptignore` files to exclude specific files or directories from being consolidated.
- **Preview Large Files:** Automatically truncates the content of large files, providing a preview of the first few lines.
- **Custom Ignore Patterns:** Add additional ignore patterns during execution to fine-tune which files to include.
- **Depth Control:** Limit the directory depth to control how deep the script traverses into the repository.
- **Progress Feedback:** Provides a visual progress bar while processing files.
- **Output Summary:** Displays the number of lines and the size of the output file once processing is complete.

## Installation

To install `git2ai`, simply clone the repository and install it using `pip`:

```bash
pip install .
