# orangeboard-modules

**orangeboard-modules** is a repository containing third-party modules that extend the functionality of the **orangeboard-core** server management application. These modules provide additional features that can easily be integrated into the core system through a drag-and-drop process.

## Features

- **Extend Functionality**: Add new tools and features to orangeboard-core, such as enhanced resource monitoring, file management utilities, and more.
- **Easy Integration**: Modules can be seamlessly added to orangeboard-core by simply copying them into the modules folder.
- **Modular Structure**: Each module works independently, so you can choose which features to add without affecting the core system.

## Getting Started

1. **Clone the repository**:
git clone https://github.com/d1zxult/orangeboard-modules.git

2. **Add the module**: Copy the selected module into the `modules` folder within the **orangeboard-core** project.

## Usage

- Modules will automatically be detected by **orangeboard-core** and displayed in the user interface.
- Use the module-specific features as described in their respective documentation.

## License

This project is licensed under the MIT License. See the LICENSE.md file for more details.

## Contributing

If you'd like to contribute, please fork the repository and submit a pull request for any improvements or bug fixes.

## Acknowledgments

A special thanks to all contributors for their efforts and contributions.

## Commit Guidelines

To maintain clear commit history, use the following naming conventions:

| Type     | Description                                                      |
|----------|------------------------------------------------------------------|
| build    | Build process updates or changes to dependencies                 |
| sec      | Security fixes or vulnerability patches                          |
| ci       | CI configuration and script updates                              |
| docs     | Documentation updates                                            |
| feat     | Introduction of new features                                     |
| fix      | Bug fixes                                                        |
| perf     | Performance improvements                                         |
| refactor | Code refactoring without adding features or fixing bugs          |
| revert   | Revert to previous commits                                       |
| style    | Code style changes (e.g., formatting, missing semicolons)        |
| test     | Adding or updating tests                                         |
