# Agency Astro Theme

Agency is an Astro theme for a Company or business or Agency marketing websites. You get a landing page that you can use to showcase everything about your company. You can easily create additional pages in markdown using the generic page layout.

[Demo Preview](https://astro.devpractical.com)

## Usage

1. Clone the project locally:

```
git clone
```

2. Enter your project directory:

```
cd agency-astro-theme
```

3. Install project dependencies.

```
npm install
```

4. Run project locally.

```
npm run dev
```

Open your browser and visit the link provided in your terminal. Most times it is usually:

```
http://localhost:3000
```

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```

/
├── public/
├── src/
│ └── pages/
│ └── index.astro
└── package.json

```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:3000`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |
