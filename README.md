# WSE Blog Post

## Project Overview
This repository contains files for the WSE Blog Post project created during a hackathon. The blog is designed to share insights, tutorials, and updates related to web software engineering (WSE) topics. It features a responsive design, interactive elements, and a collection of carefully crafted articles.

## Files and Directories

### `/WSE BLOG POST/`
The main project directory containing all source files, assets, and documentation needed to run the blog. This directory is organized to separate content, styling, functionality, and media resources for better maintainability and organization.

### `/WSE BLOG POST/index.html`
The main landing page for the blog, serving as the entry point for all visitors. This HTML5 file contains the complete structure of the homepage including:
- A responsive navigation bar with links to categories and important pages
- A featured post carousel showcasing the latest or most popular articles
- A grid layout of recent blog posts with thumbnails and excerpts
- A sidebar with search functionality, tag cloud, and newsletter subscription form
- Footer with contact information, social media links, and copyright notice
The file implements semantic HTML elements for better accessibility and SEO performance.

### `/WSE BLOG POST/styles.css`
An extensive CSS stylesheet that defines the visual appearance and responsive layout of the entire blog. Key features include:
- Custom color scheme and typography system with variables for easy theming
- Responsive grid layout that adapts seamlessly from mobile to desktop screens
- Animation effects for interactive elements like buttons, cards, and navigation
- Dark/light mode toggle functionality with appropriate color adjustments
- Custom styling for form elements, code snippets, and embedded media
- Performance optimizations with selective use of flexbox and grid layouts
The CSS follows BEM naming convention for better organization and maintainability.

### `/WSE BLOG POST/scripts.js`
A comprehensive JavaScript file implementing all interactive functionality of the blog, including:
- Dynamic content loading for blog posts to improve initial page load speed
- Comment system with form validation and submission handling
- Search functionality with filtering and highlighting of results
- Analytics tracking for user engagement and popular content
- Social media sharing integration with custom share counts
- Lazy loading of images and media for better performance
- Theme switching logic and user preference storage
The code is organized using modern JavaScript practices and is thoroughly commented for clarity.


### `/WSE BLOG POST/posts/`
A structured directory containing all blog post content, organized by:
- Individual markdown files for each article with frontmatter for metadata
- Categorized subdirectories for better organization (tutorials, news, case studies)
- Supporting materials for each post including code samples and downloadable resources
- JSON files with post metadata used by the search and filtering functionality
- Draft posts in separate folders for content under development
Each post follows a consistent format with title, author info, publication date, tags, and content sections.

## Setup and Usage
1. Clone this repository to your local machine using `git clone [repository-url]`
2. Open the `index.html` file in a web browser to view the blog locally
3. To add new posts, create new files in the `/posts/` directory following the existing naming convention and format
4. For development, consider using a local server (like Live Server in VS Code) for the best experience
5. Modify the `config.js` file to update site-wide settings like title, description, and feature flags

## Technologies Used
- HTML5 for semantic markup and structure
- CSS3 with custom properties and responsive design principles
- JavaScript ES6+ for interactive features and DOM manipulation
- Markdown for simplified content creation and management
- Font Awesome for scalable vector icons
- Google Fonts for typography enhancements
- LocalStorage for preserving user preferences


## License
This project is licensed under the MIT License - see the LICENSE file for details.
