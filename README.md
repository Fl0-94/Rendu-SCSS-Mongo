# My Project

This is a project that follows the 7-1 architecture pattern for SASS. The 7-1 pattern is a common structure for organizing SASS files in a project. It involves splitting up the SASS code into 7 different folders for a total of 7 categories, and then compiling it all into 1 output CSS file.

## Project Structure

The project is structured as follows:

- `sass/abstracts`: This directory contains all the SASS variables and functions that are used throughout the project.
- `sass/base`: This directory contains the base styles for the project, such as reset styles and typography styles.
- `sass/components`: This directory contains the styles for individual components, such as buttons.
- `sass/layout`: This directory contains the styles for larger layout components, such as headers and footers.
- `sass/pages`: This directory contains page-specific styles.
- `sass/themes`: This directory contains styles related to the theme of the project.
- `sass/vendors`: This directory contains any styles from third-party libraries or frameworks.
- `sass/main.scss`: This is the main SASS file that imports all other SASS files.
- `css/style.css`: This is the main CSS file that is generated from the SASS files.

## Setup

To set up this project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the necessary dependencies.
4. Run the build script to compile the SASS files into CSS.

## Usage

To use this project, simply link the `css/style.css` file in your HTML files. You can modify the SASS files as needed to suit your project's needs, and then recompile the CSS.

## Contributing

Contributions are welcome. Please submit a pull request with any changes.

## License

This project is licensed under the MIT License.