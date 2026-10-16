# News Author Page

A dynamic web application built as part of the freeCodeCamp JavaScript Algorithms and Data Structures certification. This application fetches author data from an external JSON API and presents it in a clean, paginated grid format with a "Load More" feature.

## Features

Asynchronous Data Fetching: Retrieves author profiles (names, avatars, bios, and links) dynamically using the JavaScript fetch API and async/await.

Pagination / Lazy Loading: Displays authors in batches of 8 using slice logic, allowing users to load more content seamlessly via a dedicated button.

Dynamic UI State Management: Automatically disables the "Load More" button and updates its text content when all available author data has been fetched.

Bio Truncation: Gracefully truncates long author biographies to maintain a consistent card layout while providing full accessibility and links to original author pages.

Error Handling: Gracefully handles network or parsing failures with a custom error message container.

### Built With

HTML5: Semantic document structure.

CSS3: Custom styling and responsive card grid layout.

JavaScript (ES6+): DOM manipulation, asynchronous programming, array methods (slice, forEach), and event listeners.

## Project Structure

index.html # Main HTML structure
style.css # Stylesheet for layout and component design
script.js # JavaScript logic for API requests and DOM rendering

### Getting Started & Installation

To run this project locally on your machine, follow these simple steps:

### Clone the repository

Navigate into the project directory:

cd freecodecamp-news-author-page

Open the project:

Open index.html directly in your preferred web browser, or use a live server extension (such as Live Server in VS Code) to view it locally.
