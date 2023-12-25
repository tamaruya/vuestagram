# vuestagram

# Vue.js Instagram

This is a Vue.js website for creating and publishing blog posts. Users can write content, add images, apply filters, and publish their posts. The website also allows users to view a feed of existing posts and navigate through different steps of the posting process.

## Project Setup

## Installing Dependencies
Before running the project, make sure to install the required dependencies. Use the following commands:

### Install Axios for making HTTP requests
npm install axios

### Install Mitt library for communication between components
npm install mitt

### Install Vuex for state management
npm install vuex@next --save

### Running the App
npm run serve

The app will be accessible at http://localhost:8080/ by default.

## Features
- Post Creation: Users can create new blog posts by following a step-by-step process.
- Image Upload: Allows users to upload images for their blog posts.
- Feed: Displays a feed of existing blog posts.
- Filter Application: Users can apply filters to their posts.
- Publishing: Users can publish their posts, making them visible in the feed.

## Project Structure
- src/App.vue: Main component containing the app's structure and logic.
- src/postdata.js: Initial post data.
- src/store.js: Vuex store for state management.
- src/components/...: Child components having different responsibilities for rendering website interface.

## Built With
- Vue.js
- Axios
- Mitt
- Vuex

## Usage
Write a new blog post by following the step-by-step process.
Upload images to include in your post.
Apply filters to enhance your post.
Write post content and username.
Publish your post, making it visible in the feed.

## Author
Kim Anna
