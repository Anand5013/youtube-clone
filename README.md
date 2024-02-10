# YouTube Clone

A YouTube clone web app built with React.js, Material UI, and Rapid API.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [API Integration](#api-integration)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview

This project replicates YouTube's core features using React.js. It utilizes Material UI for a modern interface and integrates Rapid API for fetching YouTube data.

## Features

- Trending videos
- Video search
- Video details view
- Channel details view

## Demo

Explore the live demo [here](<https://incredible-speculoos-d6bd9a.netlify.app/>).

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Anand5013/youtube-clone.git
   cd youtube-clone
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up Rapid API key:**
  - Create a `.env` file in the project root.
  - Add your Rapid API key in the `.env` file:
   ```bash
   REACT_APP_RAPID_API_KEY=your-api-key-here
   ```

4. **Run the app:**

   ```bash
   npm start
   ```
   Open http://localhost:3000 in your browser.


## API Integration
API integration is handled in `src/utils/fetchFromAPI.js`. The Rapid API key is accessed using `process.env REACT_APP_RAPID_API_KEY`.

## Technologies Used
- React.js
- Material UI 5
- React Hooks
- Axios
- Rapid API

## Author
ANAND B
