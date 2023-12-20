# CSZip README

## Project Overview
CSZip is a C# application that provides a user interface for zipping and unzipping files and directories. It leverages the Ionic.Zip library to handle compression and decompression tasks. This README file outlines the technical details and tasks related to the CSZip project.

## Table of Contents
1. [Dependencies](#dependencies)
2. [Getting Started](#getting-started)
3. [Features](#features)
4. [Usage](#usage)
5. [Known Issues](#known-issues)
6. [Contributing](#contributing)

## Dependencies
CSZip relies on the following libraries and tools:

- .NET Framework
- Ionic.Zip Library

Make sure these dependencies are installed on your system before attempting to build or run the application.

## Getting Started
To get started with CSZip, follow these steps:

1. Clone the repository to your local machine.
2. Open the solution in Visual Studio or your preferred C# IDE.
3. Build the solution to ensure all dependencies are resolved.
4. Run the application.

## Features
CSZip offers the following key features:

- Zip files and folders with optional password protection.
- Unzip files with the ability to handle existing files through user prompts.
- User-friendly interface for selecting files and folders.

## Usage
### Choosing Files or Folders
1. Click the "Choose" button to open a file or folder selection dialog.
2. Select one or more files or a single folder.

### Zipping Files
1. After choosing files or a folder, click the "Zip" button.
2. Choose a destination for the zip file and provide an optional password.
3. Click "Save" to create the zip file.

### Unzipping Files
1. Click the "Unzip" button.
2. Choose an existing zip file for extraction.
3. Select a destination folder for the extracted files.
4. Handle existing files by choosing to overwrite, skip, or cancel.

## Known Issues
- No support for handling file conflicts during the unzip process (e.g., merging folders).
- Limited error handling in case of unexpected issues.

## Contributing
Contributions are welcome! If you find a bug, have an enhancement idea, or want to contribute in any way, please submit an issue or create a pull request.

### Screenshots
![](https://github.com/AzizTalantbekuulu/CSZip_project/blob/master/Screenshot_4.png)
