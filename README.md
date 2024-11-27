# Meme Website using Flask and JSON API

This project is a simple Flask-based web application that fetches memes from a public JSON API and displays them on a web page. The meme and subreddit information is dynamically fetched and displayed, with the image refreshing every 30 seconds.

## Features

- Displays a random meme fetched from the [Meme API](https://meme-api.com/).
- Shows the name of the subreddit the meme was fetched from.
- Minimalistic design using Flask templates.

## How It Works

1. **Backend**: 
   - The Flask app fetches data from the Meme API.
   - It extracts the meme image URL and the subreddit name from the API response.

2. **Frontend**:
   - A simple HTML template (`index.html`) displays the meme and subreddit information.

3. **Dynamic Updates**:
   - Each time the page is refreshed, a new meme is fetched from the API.

## Installation and Setup

### Prerequisites
- Python 3.x
- Pip (Python package manager)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Qoslaye/Flask-Meme-Website.git
   cd Flask-Meme-Website
