# Storage & Transformation: Simple Way to Think About Information

Most recently built version of the book [available on GitHub Pages](https://likeshumidity.github.io/book-storage-and-transformation).


## Building Book
Built with [mdBook](https://rust-lang.github.io/mdBook).

### Dependencies
- [rust](https://www.rust-lang.org/)
- [cargo](https://doc.rust-lang.org/cargo/)
- [mdBook](https://rust-lang.github.io/mdBook/)

### Installing

```bash
book-storage-and-transformation/$ cargo install mdbook

book-storage-and-transformation/$ mdbook serve --open  # opens web browser to book
```

### Configuring

You can change the configuration using the `book-storage-and-transformation/book.toml` file in the root.
- [mdBook Documentation - Configuration](https://rust-lang.github.io/mdBook/format/configuration/index.html)
- [ ] #todo - add [Tufte CSS](https://edwardtufte.github.io/tufte-css/) style scheme


### Building

```bash
book-storage-and-transformation/$ mdbook build  # builds to /docs by default for publish on Github Pages
```

--

&copy; Copyright Jacob Joseph 2024. All Rights Reserved.
