# Hugo Theme Stack

## Project Overview

This is a Hugo theme project for the "Stack" theme, a card-style theme designed for bloggers. The theme is authored by Jimmy Cai and licensed under the GNU General Public License v3.0.

The theme is well-structured and provides a lot of features, including a responsive layout, dark mode, client-side search, and a variety of shortcodes. It also has excellent internationalization support.

## Key Technologies

*   **Hugo:** The theme is built for the Hugo static site generator.
*   **Go:** The theme uses Go modules for dependency management.
*   **SCSS:** The theme uses SCSS for styling, with a well-organized partials structure.
*   **TypeScript:** The theme uses TypeScript for client-side scripting, including a client-side search implementation.

## Building and Running

While there are no explicit build commands in the project files, you can likely run the project using the standard Hugo command:

```bash
hugo server
```

For more detailed instructions, refer to the official documentation at [stack.jimmycai.com](https://stack.jimmycai.com).

## Directory Structure

Here is a breakdown of the most important directories and files in the theme:

### `/archetypes`

This directory contains the content templates for the theme. The `default.md` file defines the default front matter for new content.

### `/assets`

This directory contains the theme's assets, including SCSS, TypeScript, icons, and images.

*   **`/assets/scss`**: Contains the SCSS files for styling the theme. `style.scss` is the main entry point.
*   **`/assets/ts`**: Contains the TypeScript files for client-side scripting. `main.ts` is the main entry point, and `search.tsx` provides the client-side search functionality.
*   **`/assets/icons`**: Contains the SVG icons used in the theme.
*   **`/assets/img`**: Contains images, such as the author's avatar.

### `/data`

This directory contains data files used by the theme. The `external.yaml` file is used to load external assets, such as the KaTeX library.

### `/i18n`

This directory contains the translation files for the theme. The theme supports a wide range of languages.

### `/layouts`

This directory contains the layout files for the theme.

*   **`/_default`**: Contains the default layouts for list pages (`list.html`), single pages (`single.html`), and the base template (`baseof.html`).
*   **`/partials`**: Contains the partial templates used throughout the theme, such as the article layout, sidebar, and widgets.
*   **`/shortcodes`**: Contains the shortcode templates, such as `chat.html`, `toggle.html`, and `youtube.html`.

### `/.github`

This directory contains the project's contribution guidelines and issue templates.

## Development Conventions

*   **Content:** New content should be created using the `hugo new` command, which will use the templates in the `archetypes` directory.
*   **Styling:** Styles are written in SCSS and located in the `assets/scss` directory.
*   **Client-side Scripting:** Client-side scripts are written in TypeScript and located in the `assets/ts` directory.
*   **Layouts:** The theme layouts are located in the `layouts` directory.
*   **Internationalization (i18n):** Translation files are located in the `i18n` directory.
*   **Issue Reporting:** Issues should be reported using the templates in the `.github/ISSUE_TEMPLATE` directory.
