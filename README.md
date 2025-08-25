
# Unsplash Image Gallery

A React application built with Vite that integrates the Unsplash API to browse, search, and display high-quality images. The project uses React Bootstrap for styling and the Fetch API for handling requests.

## Features

* Search photos by keyword
* Browse curated and trending collections
* View image details with a clean UI
* Responsive design for desktop and mobile

## Tech Stack

* Vite – Frontend build tool
* React – UI library
* React Bootstrap – Styling and components
* Unsplash API – Image data
* Fetch API – Data fetching

## Getting Started

### Prerequisites

* Node.js (v16 or higher recommended)
* npm or yarn

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/unsplash-gallery.git
   cd unsplash-gallery
   ```
2. Install dependencies:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```
3. Create a `.env` file in the root directory and add your Unsplash API key:

   ```
   VITE_UNSPLASH_ACCESS_KEY=your_access_key_here
   ```
4. Start the development server:

   ```bash
   npm run dev
   ```

   or

   ```bash
   yarn dev
   ```

## Usage

* Open the app in your browser at `http://localhost:5173` (default Vite port).
* Use the search bar to find images.
* Browse through results or curated collections.

## Project Structure

```
src/
  components/    # Reusable UI components
  pages/         # Main pages (Home, Search, etc.)
  services/      # API fetch utilities
  App.jsx        # Main application component
  main.jsx       # Entry point
```

## Future Improvements

* Add infinite scrolling or pagination
* Enable user authentication for personal collections
* Add download and share options

## License

This project is licensed under the MIT License.

