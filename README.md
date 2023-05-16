# Movie Search Website

This is a website that allows users to search for movies. The site retrieves movie data from an external API and displays information such as the movie's IMDb rating, poster, genres, release year, duration, summary, and cast.

## Features

- Search for movies using the search bar.
- Display movie details including IMDb rating, poster, genres, release year, duration, summary, and cast.
- Responsive design for optimal viewing on different devices.

## Technologies Used

- HTML: Markup language for structuring the web pages.
- CSS: Styling language used for visual presentation.
- JavaScript: Programming language for implementing dynamic functionality.
- API: Retrieve movie data from an external source.
- [External API Name]: The specific API used for retrieving movie data.

## Usage

1. Enter a movie title in the search bar.
2. Click the search button or press Enter.
3. The website will fetch movie data from the API and display the results.
4. Click on a movie to view its details.

## API Configuration

To retrieve movie data from the external API, you will need an API key. Follow these steps to set up the API:

1. Go to https://www.omdbapi.com/apikey.aspx 
2. Generate an API key in your account settings.
3. Create a new file named `key.js` in the project directory.
4. Add the following code to `key.js`:

```javascript
key = "YOUR_API_KEY";
```

5. Replace `'your-api-key'` with your actual API key.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.
