# Gaming Website Project

A modern, responsive gaming website built with Next.js that showcases various video games with detailed information, ratings, and categorization.

## Features

- 🎮 Extensive game catalog with detailed information
- 🔍 Browse games by categories
- ⭐ Rating system for games
- 📱 Fully responsive design
- 🎯 Interactive UI with hover effects
- 🖼️ Beautiful game imagery showcase
- 📄 Detailed game pages with specifications

## Tech Stack

- [Next.js](https://nextjs.org/) - React framework for production
- [Tailwind CSS](https://tailwindcss.com/) - For styling and responsive design
- [React Icons](https://react-icons.github.io/react-icons/) - For beautiful icons
- [TypeScript](https://www.typescriptlang.org/) - For type safety

## Getting Started

### Prerequisites

Make sure you have Node.js installed on your system.

### Installation

1. Clone the repository:

```bash
git clone [your-repository-url]
```

2. Navigate to the project directory:

```bash
cd gaming-website-project-task
```

3. Install dependencies:

```bash
npm install
```

### Running the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

```
src/
├── app/
│   ├── globals.css    # Global styles
│   ├── layout.tsx     # Root layout component
│   ├── page.tsx       # Home page
│   ├── data/
│   │   └── games.ts   # Games data
│   └── games/
│       ├── page.tsx           # Games listing page
│       └── [...slug]/
│           └── page.tsx       # Individual game page
```

## Key Features Implementation

- **Game Catalog**: Browse through a collection of games with grid layout
- **Interactive UI**: Hover effects and smooth transitions for better user experience
- **Game Details**: Detailed view for each game including:
  - Rating
  - Release Date
  - Developer Information
  - Game Description
  - Game Categories

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
