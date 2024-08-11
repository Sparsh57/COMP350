# pyls

`pyls` is a command-line tool implemented in Python that mimics the behavior of the Unix `ls` command, with some limited functionalities. This tool lists files and directories in the current working directory with various options for formatting.

## Features

- **Basic Listing**: 
  - `pyls`: Lists all files and directories in the current working directory.
  
- **File Type Suffixes**: 
  - `pyls -F`: Lists all files and directories, appending a `/` to directories and `*` to executables.
  
- **Detailed Listing**: 
  - `pyls -l`: Displays a detailed list with the last modified date, file size, and name.
  
- **Combined Detailed and Suffix Listing**: 
  - `pyls -l -F`: Combines the detailed listing with file type suffixes.
  
- **Help**: 
  - `pyls -h` or `pyls --help`: Displays usage information and available options.

## Installation

To install the `pyls` tool, clone the repository and set it up in your local environment:

```bash
git clone https://github.com/Sparsh57/pyls.git
cd pyls
