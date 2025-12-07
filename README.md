# Hello Marp Project

This project provides a setup and examples for creating presentation slides from Markdown using Marp.

## Setup
```bash
pnpm install
```

## Creating and Converting Slides

Edit `slide.md` to create your slides.

You can convert your slides to various formats using the following commands. Output files will be generated in the `example/` directory.

-   **Convert to HTML**:
    ```bash
    pnpm build:html
    ```
-   **Convert to PDF**:
    ```bash
    pnpm build:pdf
    ```
-   **Convert to PowerPoint (PPTX)**:
    ```bash
    pnpm build:pptx
    ```
-   **Watch for changes and auto-update (HTML)**:
    ```bash
    pnpm watch
    ```

## Marp Feature Examples

`slide.md` includes examples demonstrating the following Marp features:

-   Theme settings
-   Pagination
-   Shared header and footer
-   Slide-specific style adjustments
-   Background image configuration (supports local images)
-   Code blocks
-   Mathematical expressions (MathJax)
-   Fixed titles using absolute positioning