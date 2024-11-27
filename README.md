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

---
## 📸 Screenshots
---
<img width="927" alt="1" src="https://github.com/user-attachments/assets/20142e67-ebc9-4066-b438-279b5f19bd01">
<img width="929" alt="2" src="https://github.com/user-attachments/assets/5ad5c698-d741-495a-a7a4-a3a1026ec8f6">
<img width="928" alt="3" src="https://github.com/user-attachments/assets/04d70768-9d09-4438-b5b3-c9f362207f61">
<img width="926" alt="44" src="https://github.com/user-attachments/assets/388ecf2c-3df6-418f-af1d-ce9e48837a43">
<img width="927" alt="55" src="https://github.com/user-attachments/assets/df7e1de1-9df5-49ea-8827-ac2325192de4">




### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Qoslaye/Flask-Meme-Website.git
   cd Flask-Meme-Website
