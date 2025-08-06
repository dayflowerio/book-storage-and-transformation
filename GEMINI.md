# Directory Overview

This directory contains the source files for the book "Storage & Transformation: Simple Ways To Think About Information". The book is written in Markdown and built using the `mdBook` tool.

# Key Files

*   `book.toml`: The main configuration file for the book. It defines the book's title, author, and other metadata.
*   `src/SUMMARY.md`: This file defines the structure of the book, including the order of chapters and sections.
*   `src/`: This directory contains the Markdown source files for the book's content.
*   `docs/`: This directory contains the built HTML version of the book, ready for publishing.

# Usage

This directory is used for writing and building the book.

## Building the book

To build the book, you need to have `mdBook` installed. You can install it using `cargo`:

```bash
cargo install mdbook
```

Once `mdBook` is installed, you can build the book using the following command:

```bash
mdbook build
```

This will generate the HTML version of the book in the `docs/` directory.

## Viewing the book

To view the book locally, you can use the `mdbook serve` command:

```bash
mdbook serve --open
```

This will start a local web server and open the book in your web browser.
