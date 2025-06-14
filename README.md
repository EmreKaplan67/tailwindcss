# Movie App

A modern, responsive movie application that showcases trending movies using React and Tailwind CSS. This application fetches real-time movie data from The Movie Database (TMDB) API and provides a beautiful user interface for movie enthusiasts.

## Features

- Displays trending movies with stunning posters
- Modern and responsive UI built with Tailwind CSS
- Real-time data fetching from TMDB API
- Clean and minimal design
- Fast loading and smooth performance

## Tech Stack

- React 19
- Tailwind CSS 4.1.8
- Vite for build tooling
- ESLint for code quality

## Getting Started

1. Clone the repository:
```bash
git clone [your-repo-url]
cd Movie_App
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your TMDB API key:
```env
VITE_TMDB_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173`

## Project Structure

```
src/
├── components/     # Reusable React components
├── assets/         # Static assets
├── lib/           # Utility functions and configurations
├── App.jsx        # Main application component
└── main.jsx       # Entry point
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Movie Database (TMDB) API
- React and Tailwind CSS communities