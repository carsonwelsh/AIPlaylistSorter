# AIPlaylistSorter

AIPlaylistSorter is a multi-service application that uses the [OpenAI API](https://platform.openai.com/) to classify and sort music tracks. It combines **Python** (for data ingestion & AI integration), **Go** (for backend APIs), and **JavaScript** (for the front-end UI). The project aims to intelligently reorder playlists based on mood, genre, or other creative criteria—making it easier to curate and discover music.

---

## Overview

AIPlaylistSorter lets you:

- **Fetch and analyze** song data (titles, artists, audio features, etc.).  
- **Classify tracks** by mood or genre using OpenAI’s GPT-based models.  
- **Automatically reorder** playlists based on desired criteria (e.g., tempo, energy, vibe).  
- **Generate creative descriptions** or summaries for songs or entire playlists.

It’s a great way to practice:

- Python scripting (data ingestion & prompt engineering)
- Go services (API design & concurrency)
- JavaScript front-end (UI/UX & asynchronous requests)
- Orchestrating these services together

---

## Features

1. **AI-Powered Classification**  
   Integrates with OpenAI to classify songs by mood, genre, or other categories.

2. **Playlist Sorting**  
   Automatically sorts or reorders playlists based on classification and audio features.

3. **Dynamic Descriptions**  
   Uses GPT to generate short, creative descriptions for each track or playlist.

4. **API-First Design**  
   Go-based REST or GraphQL API for easy integration with other services or front-ends.

5. **Extensible Architecture**  
   The Python service can be extended to perform additional data analysis or ML tasks.
