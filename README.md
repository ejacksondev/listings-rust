# listings-rust
A Rust language and style specification for the LaTeX-package listings

## Usage
* place the `listings-rust.sty` where `latex` can find it
* import `listings` and `listings-rust` in your LaTeX document with `\usepackage{listings, listings-rust}`
* select the language `Rust` in the `lstlistings` environment, e.g.
  ```latex
  \begin{lstlisting}[language=Rust]
  // your source code
  \end{lstlisting}
  ```
* optional: select one of the styles `colouredRust`, `uncolouredRust`, or `boxed`, e.g.
  ```latex
  \begin{lstlisting}[language=Rust, style=boxed]
  // your source code
  \end{lstlisting}
  ```
  _Please note: uncolouredRust will render with no additional colours. Use of this fork rather than the main project will result in a lack of blue hghlights on more delimiters whilst using colouredRust and boxed modes._
## Documentation
Currently there is only the style-file itself and the example document `listings-style.tex` for documentation.
