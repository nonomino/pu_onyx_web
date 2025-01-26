# CodingRedefined

## Prerequisites

Ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/) (can also use `npm`)

You will also need to install Vite globally if it's not already installed:

```bash
yarn global add vite
```

## Installation

1. Clone this repository:

```bash
git clone https://github.com/nonomino/pu_onyx_web
```

2. Navigate to the project directory:

```bash
cd pu_onyx_web
```

3. Install dependencies:

```bash
yarn
```

## Development

To start the development server, run:

```bash
yarn dev
```

This will start the Vite development server. Open your browser and navigate to http://localhost:5173 to view the project.

## Building for Production

To create a production build, run:

```bash
yarn build
```

The production-ready files will be in the dist/ directory.

## Previewing the Production Build

To preview the production build locally:

```bash
yarn preview
```

## Project Structure

.
├── index.html       # Main entry point
├── src/             # Source files (JavaScript, CSS, etc.)
│   ├── main.js      # Entry script
│   ├── main.css     # Styles including Bulma
├── node_modules/    # Installed dependencies
├── package.json     # Project configuration
└── yarn.lock        # Dependency lock file

## Dependencies

Bulma: CSS framework.

Iconoir: Icon library.

## License

This project is licensed under GNU GPL v3.0
