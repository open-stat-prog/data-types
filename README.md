# Template Repository for OSP Modules

This module provides the framework to set up a new Open Statistical Programming Tutorials module.

## Using the Template

1. Create a new repository using the `open-stat-prog/module-template` repository template.
1. Clone the repository.
1. Navigate to the module root directory on your machine and run `renv::restore()`.
   - You can also just source `R/install_packages.R`, since renv restore is the only uncommented command in that file.
1. Render the site to make sure everything's working properly.
   - Run `quarto render` from within the project directory.
1. Replace the placeholder content with your own material.

## Style Guidelines

- Follow the [tidyverse style guide](https://style.tidyverse.org/).
- Break long lines at 120 characters (approximately).
   - Don't rely on your IDE's visual line breaking feature: actually break the lines in the source code.
- No spaces in file names.
   - Don't be a jerk.
   - This is not negotiable.
   - If I find a space in any of your file names, I will find you, and I will hurt you.
- Use `lower_snake_case` for file and directory names.
- Use `lower_snake_case` or `lowerCamelCase` for variable names.
- Don't get too creative (or lazy) with the directory structure.
   - Make a reasonable effort to use the structure defined in the template repo.

## Intellectual Property and Privacy

Be mindful of intellectual property rights and privacy restrictions when incorporating external resources into your module.

- Don't include any materials that you don't have the right to distribute.
- If the licensing situation is questionable, don't include the content.
- Make a reasonable effort to attribute credit for any resources your incorporate into your module.
- Don't distribute sensitive data with your module.
   - In most cases, this mean you shouldn't be using real-world research data for examples.
