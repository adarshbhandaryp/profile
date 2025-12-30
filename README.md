# Adarsh Bhandary Panambur - Portfolio Website

This is a premium personal portfolio website built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com). It is designed to be hosted on GitHub Pages at `https://adarshbhandaryp.github.io/profile/`.

## 🚀 Project Structure

- `src/components`: UI components (Hero, Nav, ProjectCard, etc.)
- `src/layouts`: Base layout with global styles and meta tags.
- `src/pages`: The main entry point (`index.astro`).
- `src/data`: JSON files containing the content (Resume, Projects, etc.).
- `src/styles`: Global CSS (custom fonts, animations, noise texture).

## 🛠️ Local Development

1.  **Install Dependencies**:
    ```bash
    npm install
    ```

2.  **Start Development Server**:
    ```bash
    npm run dev
    ```
    Open your browser to `http://localhost:4321/profile/`.

3.  **Build for Production**:
    ```bash
    npm run build
    ```
    The output will be in the `dist/` directory.

## 📦 Deployment

This project is configured to deploy automatically to GitHub Pages using GitHub Actions.

1.  Push this code to your repository: `https://github.com/adarshbhandaryp/profile`
2.  Go to **Settings > Pages** in your GitHub repository.
3.  Under **Build and deployment**, select **GitHub Actions** as the source.
4.  The workflow defined in `.github/workflows/deploy.yml` will automatically build and deploy the site on every push to `main`.

## 📝 Customization

- **Content**: Update the JSON files in `src/data/`.
- **Styles**: Modify `tailwind.config.mjs` for colors and `src/styles/global.css` for global styles.
- **Base Path**: If deploying to a different path, update `base` in `astro.config.mjs`.
