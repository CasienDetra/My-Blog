# Yanouk's Blog

This is a personal blog powered by Hugo, using a customized version of the PaperMod theme. It features various posts on topics like productivity, technology, and self-improvement.

## Features

*   **Hugo Static Site Generator**: Fast and flexible static site generation.
*   **PaperMod Theme**: A clean, fast, and responsive theme for Hugo.
*   **Sakura Falling Petals Effect**: Integrated a beautiful falling cherry blossom petal effect for an enhanced visual experience.
*   **Content Management**: Posts organized by categories and tags.
*   **Search Functionality**: Built-in search for easy content discovery.
*   **Responsive Design**: Optimized for various screen sizes.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   **Hugo**: Ensure you have Hugo installed. You can download it from [Hugo's official website](https://gohugo.io/getting-started/installing/).
    *   Verify installation: `hugo version`
*   **Git**: Required for cloning the repository and managing themes.

### Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/ARtBlog.git # Replace with your actual repo URL
    cd ARtBlog
    ```

2.  **Initialize and update themes**:
    This project uses Hugo themes as Git submodules.
    ```bash
    git submodule update --init --recursive
    ```

3.  **Install Node.js dependencies for Sakura theme (if needed for development)**:
    The `themes/sakura` directory contains `package.json` and `yarn.lock`, indicating it might have its own build process for assets. While the falling effect was directly integrated, if you plan to modify the original Sakura theme, you might need to install its dependencies:
    ```bash
    cd themes/sakura
    npm install # or yarn install
    cd ../..
    ```

## Running the Project

To run the Hugo site locally:

1.  **Build and serve the site**:
    ```bash
    hugo server
    ```
    Hugo will typically serve the site at `http://localhost:1313/` or an available port if 1313 is in use. The terminal output will provide the exact URL.

2.  **View in browser**: Open your web browser and navigate to the URL provided by the `hugo server` command (e.g., `http://localhost:63478/`). You should see the blog with the PaperMod theme and the integrated falling cherry blossom effect.

## Project Structure

*   `content/`: Your blog posts and other pages (e.g., `about.md`, `posts/`).
*   `themes/PaperMod/`: The main theme used for the blog.
*   `themes/sakura/`: The 'sakura' theme, from which the falling flower effect was extracted.
*   `assets/`: Custom assets for your site, including `css/sakura-effect.css` and `js/sakura-effect.js` for the falling petals.
*   `hugo.yaml`: Main Hugo configuration file.
*   `public/` and `docs/`: Generated static files after building the Hugo site.

## Customization

*   **Content**: Add new posts to the `content/posts/` directory.
*   **Configuration**: Modify `hugo.yaml` to change site title, menu, social links, and other PaperMod specific parameters.
*   **Sakura Effect**:
    *   `assets/js/sakura-effect.js`: Adjust parameters like `fallSpeed`, `maxSize`, `minSize`, `delay`, and `colors` within the `Sakura` constructor options to customize the falling petals.
    *   `assets/css/sakura-effect.css`: Modify the `@keyframes` animations or `.sakura` class styles for advanced visual changes to the petals.

## Contributing

Feel free to fork this repository and make your own modifications.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details. (Note: Individual themes like PaperMod and Sakura may have their own licenses.)
