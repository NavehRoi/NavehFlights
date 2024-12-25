# Flight Naveh - Flight Search and Details

## Overview
Flight Naveh is a web-based application that allows users to search for flights, view flight details, and explore more information about each flight in a user-friendly interface. The application is built with HTML, CSS (Bootstrap), and JavaScript, providing an interactive way to manage and view flight data. It integrates with the Amadeus API to retrieve real-time flight data and the OpenAI API to provide tips and answer user questions.

## Features
- **Flight Listing**: Displays a list of flights retrieved from the Amadeus API via the backend.
- **Expandable Cards**: Users can click on flight cards to view additional details or display the details in a modal popup.
- **AI Integration**: Users can search for tips related to their destination, dates, or other travel-related data using OpenAI.
- **Question Box**: Includes a text box where users can ask travel-related questions and get instant AI-generated responses.
- **Navigation**: A "Back to Search" button allows users to return to the search page.

## Usage

### Viewing Flight Details
- The flights are displayed as cards. Click on a card to:
  - Expand and show more details.
  - Optionally, trigger a modal popup to display flight information in a centralized view.

### Using the AI Integration
- Enter your query into the question box (e.g., "What are some tips for traveling in winter?").
- Click the "Search" button to get AI-generated tips or data relevant to your search.

### Navigation
- Use the "Back to Search" button to navigate back to the flight search page (`flightSearch.html`).

## Technologies Used
- **HTML**: Markup for the structure of the web application.
- **CSS (Bootstrap)**: Styling and responsive layout.
- **JavaScript**: Handles dynamic behavior, including event listeners, modal interactions, and OpenAI integration.
- **Amadeus API**: Provides real-time flight data via the backend.
- **OpenAI API**: Provides AI-generated responses for user queries.

## Author
Naveh

Enjoy your flight search experience with Flight Naveh!

