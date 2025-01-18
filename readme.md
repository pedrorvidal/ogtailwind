# ogTailwind

## Description

ogTailwind is a project that utilizes Tailwind CSS for styling.

## Getting Started

### Prerequisites

- Node.js and npm (or yarn) installed on your system
- Tailwind CSS installed as a dev dependency

### Installation

1. Clone the repository: `git clone git@github.com:pedrorvidal/ogtailwind.git`
2. Install dependencies: `npm install` (or `yarn install`)

### Installation a new project

```sh
npm install -D tailwindcss
npx tailwindcss init
```

### Configuration

```json
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ['./src/**/*.{html,js}'],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

### Run

1. Start the development server: `npm start` (or `yarn start`)
2. Open your web browser and navigate to `http://localhost:3000`
3. npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

### Deploy

1. Build the project: `npm run build`
2. Deploy the built project to your preferred hosting platform (e.g. Vercel, Netlify, GitHub Pages)

## License

- [MIT License](https://opensource.org/licenses/MIT)

## Authors

- Pedro R. Vidal
