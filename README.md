# RoboFriends

A modern React application that displays robot friends with search functionality. Built with React 19 and Vite.

## Features

- **Robot Cards**: Display robot friends fetched from an API
- **Search Functionality**: Filter robots by name in real-time
- **Responsive Design**: Built with Tachyons CSS framework
- **Smooth Scrolling**: Custom scroll component for better UX

## Tech Stack

- **React 19** - Latest React with modern features
- **Vite** - Fast build tool and development server
- **Tachyons** - Functional CSS framework
- **JSONPlaceholder API** - Mock data for robot information

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/robofriends-latest.git
   cd robofriends-latest
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run deploy` - Deploy to GitHub Pages
- `npm run lint` - Run ESLint

## Deployment

The app is configured for deployment to GitHub Pages. To deploy:

```bash
npm run deploy
```

The deployed version is available at: [https://aneagoie.github.io/robofriends-latest/](https://aneagoie.github.io/robofriends-latest/)

## Project Structure

```
src/
├── components/
│   ├── Card.jsx          # Individual robot card component
│   ├── CardList.jsx      # List of robot cards
│   ├── Scroll.jsx        # Scroll wrapper component
│   └── SearchBox.jsx     # Search input component
├── containers/
│   ├── App.jsx           # Main application component
│   └── App.css           # Application styles
├── main.jsx              # Application entry point
├── index.css             # Global styles
└── robots.jsx            # Robot data (if used)
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is part of the Zero to Mastery React course.

## Learn More

Visit [Zero to Mastery](https://zerotomastery.io/) for more tutorials and courses.
