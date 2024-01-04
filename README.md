# Sample Project

This project is a sample layout template utilizing HTML, SCSS, and JavaScript.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Describe briefly what this project is about and its purpose.

## Project Structure

Briefly explain the structure of the project and its important directories/files.

- `inc/`: Contains SCSS files for imports.
- `css/`: Stores compiled CSS files.
- `js/`: Houses JavaScript files.
- `fonts/`: Includes font files used in the project.
- `index.html`: Main HTML file.

## Usage

Provide instructions on how to use or run the project:

1. Clone this repository: `git clone https://github.com/abdurohman-karim/layout_project.git`
2. Open `index.html` in your browser to view the project.

Optionally, include any additional setup or installation instructions.

# SCSS Mixins Usage Guide

This document explains how to use the SCSS mixins provided in this project for flexible layout styling.

## `flex` Mixin

The `flex` mixin allows you to create flexible layouts using flexbox properties.


```scss
.selector {
  @include flex(row, center, flex-start);
}
```

# Grid Mixins Usage

These SCSS mixins simplify the creation of grid layouts using CSS Grid.

## Grid Container Mixin

The `grid-container` mixin helps create a grid container by defining the number of columns and gap between them.

### Usage

```scss
.container {
  @include grid-container(3, 20px);
}
.item1 {
  @include grid-item(1 / span 2, 1);
}
.item2 {
  @include grid-item(2, 2);
}

```


## Contributing

Explain how others can contribute to the project, whether through bug fixes, improvements, or new features. Include information about how to submit pull requests or raise issues.

## License

Indicate the license under which the project is distributed. Developer: @abdurohman-karim

This project is licensed under the [MIT License](LICENSE).
