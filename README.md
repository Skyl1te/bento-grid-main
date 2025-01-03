# Bento Grid Layout

This project implements a responsive, modern bento grid layout inspired by a design challenge from Frontend Mentor. The layout is visually appealing and adapts to different screen sizes, providing a smooth user experience across devices. The design is simple yet structured, allowing images and text content to be organized in a grid that adjusts itself depending on the screen width.

## Project Structure

### Files:
- `index.html`: The main HTML file that contains the structure and content of the page.
- `style.scss`: The SCSS file that contains global styles, grid setup, color variables, typography, and overall layout.
- `adaptive.scss`: The SCSS file responsible for making the layout responsive. It uses media queries to adjust the grid and typography based on different screen sizes.
- `assets/images/`: Folder containing images used in the grid.

## Features

- **Responsive Design**: 
  - The layout adjusts to different screen sizes using CSS Grid and media queries. 
  - At large screens (above 1240px), the layout uses a 3-column grid.
  - For medium screens (below 1240px), it switches to a 2-column grid.
  - For smaller screens (below 960px), the layout becomes a single-column grid for optimal readability.
  
- **Grid System**: 
  - The grid has defined areas for each item, making it easy to place content (like images and text) in different sections.
  - The content items are styled differently to match the theme and emphasize important elements.

- **Typography and Colors**:
  - The site uses a custom font family `"DM Sans"` from Google Fonts.
  - Colors are defined using CSS variables to maintain consistency throughout the site.

## Installation

To get started with this project, follow these steps:

1. Clone the repository to your local machine.
    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory.
    ```bash
    cd <project-directory>
    ```

3. Make sure you have Node.js installed. Then install the necessary dependencies.
    ```bash
    npm install
    ```

4. Compile SCSS to CSS using your preferred method (such as using `sass` or a bundler like Webpack).

5. Open `index.html` in your browser to view the layout.

## Development Setup

To make the development process easier, it is recommended to use a live server or a build tool to automatically compile SCSS into CSS.

- **SCSS to CSS compilation**:
  - If you're using `sass`:
    ```bash
    sass --watch scss/style.scss:css/style.css
    ```

## Media Queries and Responsiveness

The project includes the following breakpoints:

- **Above 1240px**: 3-column grid.
- **Below 1240px**: 2-column grid.
- **Below 960px**: Single-column grid.
- **Below 760px**: Adjusted font sizes and image alignment for a more mobile-friendly layout.

## Credits

- **Challenge**: This project was based on the **Frontend Mentor** challenge [Bento Grid Layout](https://www.frontendmentor.io).
- **Coded by**: [Skyl1te](https://github.com/Skyl1te).

---

Feel free to explore the code and modify the design as needed. The grid layout is flexible, making it suitable for various types of content.

### Acknowledgments

This design was created as part of a frontend challenge, and all images and assets are either sourced from free platforms or placeholders.