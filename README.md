# YouTube Clone Project

## Overview

This project is a YouTube clone developed using React. It provides users with a YouTube-like experience by displaying popular and current videos on the home page. The project features dynamic fetching of videos for each category, video details page with navigation between videos, related content display, and a search functionality.

## Project Structure

- **Home Page**: Displays popular and current videos.
- **Trending Videos**: Shows trending videos.
- **Category Featured Videos**: Displays videos for each category.
- **Video Details**: Allows navigation between videos with detailed information.
- **Search Results**: Provides search functionality and displays results based on keywords.

## Technologies Used

- **React**: Building components and managing the UI.
- **React Router**: Navigation between pages.
- **Axios**: Making HTTP requests.
- **Millify**: Integrating millify numbers for readability.
- **Moment**: Handling and formatting date and time.
- **React Player**: Embedding and playing videos.
- **Tailwind CSS**: Styling for a fast and customizable design.

  ## Screen
<img src="./public/clone.gif"/>

## Installation

To install the required libraries, run the following command:

```bash
npm install react-router-dom react-icons axios millify moment react-player tailwindcss

For Tailwind CSS, follow the installation instructions on the official website.

Usage

Home Page: Displays popular and current videos.
Trending Videos: Shows trending videos.
Category Featured Videos: Displays videos for each category.
Video Details: Allows navigation between videos with detailed information.
Search Results: Provides search functionality and displays results based on keywords.
Notes

Path Parameters
To access path parameters like ürünler/56, use the useParams hook.

// Example
const { productId } = useParams();

Query Parameters
For query parameters like ürünler?id=56&category=elektronik, use the useSearchParams hook.

// Example
const searchParams = useSearchParams();
const productId = searchParams.get('id');
const category = searchParams.get('categoryß');


