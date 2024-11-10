# News App

This News App allows users to browse the latest news from various categories using the News API. It offers a smooth and clean user experience for quickly accessing top headlines across different topics. The app is designed to be responsive, making it accessible on both desktop and mobile devices.

## Features

- **Category Selection**: Browse news by categories like general, entertainment, health, science, sports, and technology.
- **Dynamic News Cards**: Each article is displayed with an image, title, description, and a "Read More" link to the full article.
- **Responsive Layout**: Optimized for viewing on all screen sizes.

## Technologies Used

- **HTML, CSS, JavaScript**: Core front-end technologies for structure, styling, and interactivity.
- **News API**: Provides real-time news data.


## file structure:

- **index.html**: Main HTML file with the basic layout and elements for the news app.
- **style.css**: Contains all styling rules, making the application look polished and consistent.
- **script.js**: Holds JavaScript for fetching and displaying news data based on user-selected categories.
- **api-key.js**: This file stores the API key securely (not included in the repository to keep the key private).

## Code Explanation
The script.js file includes the main functions that drive the app’s functionality:

- **generateUI(articles)**: Generates the HTML structure for each news article card and adds it to the container.
- **getNews()**: Makes an API request to fetch news articles and updates the UI.
- **selectCategory(e, category)**: Handles category button clicks, updating the news feed based on the selected category.
- **createOptions()**: Dynamically generates buttons for each category.
- **init()**: Initializes the app by setting the default category to "general" and loading the news feed.
