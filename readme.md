# INDEE ASSIGNMENT

## Overview

This project is a simple HTML and CSS website that features a banner section and a slider for the most-watched films. It showcases the ability to create a dynamic and responsive web page with a scrolling film poster carousel.

## Project Structure

The project contains the following files:

- `index.html`: The main HTML file that contains the structure of the web page.
- `style.css`: The CSS file that contains styles for the web page.

## Features

1. **Header Section**:

   - Contains a banner with the title "Money Heist".
   - Includes two buttons: "Play" and "My List".
   - Contains a brief description of the "Money Heist" series.

2. **Most Watched Films Slider**:
   - Displays a series of movie posters.
   - Each movie poster has a one-line description.
   - Includes left and right buttons for scrolling through the movie posters.
   - Supports keyboard arrow keys for navigation.

## Setup Instructions

To set up and run this project locally, follow these steps:

1. **Clone the repository**:

   ```sh
   git clone https://github.com/yourusername/indee-assignment.git
   ```

2. **Navigate to the project directory**:

   ```sh
   cd indee-assignment
   ```

3. **Open the `index.html` file in your web browser**:
   - You can do this by simply double-clicking the `index.html` file or by opening it through your browser's file menu.

## File Details

### `index.html`

This is the main HTML file that defines the structure of the web page.

- The `<header>` section contains the banner with the title, buttons, and description.
- The `<div class="row">` section contains the slider for the most-watched films.
- Each movie poster is contained within a `<div class="row__posterContainer">` and has a `<p class="row__posterDescription">` for the description.
- JavaScript is included to handle the scrolling functionality.

### `style.css`

This CSS file contains styles for the web page.

- `.banner`: Styles for the banner section.
- `.row`: Styles for the row section containing the movie posters.
- `.row__posterContainer`: Styles for the container of each movie poster and its description.
- `.row__poster`: Styles for the movie poster images.
- `.row__posterDescription`: Styles for the movie descriptions.
- `.slider-container`: Styles for the slider container.
- `.slider-btn`: Styles for the left and right buttons.

## JavaScript Functionality

- **Scrolling**:
  - The left and right buttons scroll the movie posters smoothly.
  - The `ArrowLeft` and `ArrowRight` keys can also be used for navigation.

## Future Enhancements

- Add more interactivity, such as hover effects on movie posters.
- Implement a backend to dynamically load movie data.
- Enhance responsiveness for different screen sizes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

- This project was developed as part of an assignment for INDEE.

## Contact

If you have any questions or suggestions, please feel free to contact [your name] at [your email].
