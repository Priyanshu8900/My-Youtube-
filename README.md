# My-Youtube-
Youtube clone
This project is a clone of the popular video-sharing platform YouTube, developed as a part of Akshay Saini's Namaste React course. It is built using modern front-end technologies, including React, Redux Toolkit, TailwindCSS, and other libraries.

## Features

- **YouTube Clone:** The project is a replica of the YouTube platform, including its UI design and functionalities.
- **YouTube Video List:** The app displays a paginated list of YouTube videos fetched from the YouTube API. The list supports lazy loading to enhance performance.
- **YouTube Video Preview:** Clicking on a video in the list opens a preview window that displays the selected video. The preview window includes basic details of the video, such as its title, description, and view count.
- **Search Suggestions:** As the user types in the search bar, the app displays a dropdown list of suggested search queries. This feature enhances the user experience and makes it easier to find relevant videos.
- **Search Caching:** To improve performance and reduce the number of API calls made, the app caches the results of previous searches. This means that if a user makes the same search query twice, the app will fetch the results from the cache instead of making a new API call.
- **Optimized Search Using Caching and Debouncing:** The app uses debouncing to optimize the search functionality. This means that instead of making an API call for every key press in the search bar, the app waits until the user has stopped typing before making the API call. Additionally, the app uses caching to fetch the results of previous searches faster.
- **Optimized API Calls Using Debouncing:** The app uses debouncing to optimize API calls throughout the app. For example, when a user scrolls through the video list, the app waits until the user has stopped scrolling before fetching more videos. This feature reduces the number of API calls made and improves performance.

- ## Usage

To use this project, follow these steps:

1. Clone the repository.
2. Install the dependencies using `npm install`.
3. Create a `.env` file in the root directory and add your YouTube API key as `GOOGLE_API_KEY=<your-api-key>`.
4. Start the development server using `npm start`
