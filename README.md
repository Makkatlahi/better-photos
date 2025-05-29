# BetterPhotos

A modern, responsive web app to help you improve your photography skills by sharing your photos and receiving feedback from a jury and the community.

## Features

- Clean, responsive layout built with SCSS and CSS Grid
- Upload photos via drag-and-drop or file browser
- Social proof with user avatars and join count
- Gallery with animated photo grid and feedback comments
- Steps section to guide new users
- Accessible and mobile-friendly design

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v12 or higher)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/Makkatlahi/better-photos.git
   cd better-photos
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

### Development

To start the Sass compiler in watch mode and work with the source files:

```sh
npm run compile
```

This will watch `src/main.scss` and output CSS to `src/style.css`.

### Production Build

To build the optimized, autoprefixed CSS for production:

```sh
npm run build:compile
npm run build:prefixes
npm run build:optimize
```

The final, optimized CSS will be in `build/style.css`.

## Project Structure

```
package.json
build/
  compiled.css      # Compiled SCSS (unprefixed, unminified)
  prefixed.css      # Autoprefixed CSS
  style.css         # Final, optimized CSS
src/
  index.html        # Main HTML file
  main.scss         # Main SCSS source
  style.css         # Development CSS output
```

## License

This project is licensed under the ISC License.

---
