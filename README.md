<div align="center">

# LaTeX Assignment Template

![LaTeX](https://img.shields.io/badge/LaTeX-Assignment-purple)
![XeLaTeX](https://img.shields.io/badge/engine-XeLaTeX-green)

A LaTeX template for short sectioned assignments, featuring New Computer Modern
fonts with full CJK (Chinese) support via XeLaTeX.

</div>

## Features

- **Fonts**: New Computer Modern (serif, sans, math) + Source Han (CJK serif, sans)
- **CJK Support**: xeCJK with bundled font files (git submodule)
- **Build**: latexmk with XeLaTeX engine

## Usage

```bash
# Clone with fonts submodule
git clone --recurse-submodules git@github.com:houchen-li/latex-assignment-template.git

# Build
latexmk main.tex

# Clean
latexmk -C
```

## Project Structure

```
├── main.tex          # Main document
├── .latexmkrc        # latexmk configuration
├── fonts/            # Font files (git submodule)
└── figures/          # Figures directory
```

## License

CC BY-NC-SA 3.0
