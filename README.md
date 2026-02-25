# 🐳 Docker Security Book Template

> *An open-source book template for the community, based on the book "Docker and Kubernetes Security" by Mohammad-Ali A'râbi.*

---

This book is written using Markdown and Pandoc. The source files are in the `chapters` directory.
The book is built using the `Makefile` and `pandoc` command:

```bash
make pdf
```

or

```bash
make epub
```

The book is built in the `output` directory.

## Install Pandoc

On Ubuntu, install Pandoc and Tex Live:

```bash
sudo apt install pandoc texlive texlive-xetex latexmk
```

On macOS, install Pandoc using Homebrew:

```bash
brew install pandoc
```

But to install Tex Live, you need to download the installer from the [Tex Live website](https://www.tug.org/mactex/mactex-download.html).
Then install `latexmk` using Tex Live's package manager:

```bash
sudo tlmgr update --self
sudo tlmgr install latexmk
```

Make sure to have the fonts installed:

```bash
brew install --cask font-fira-code
brew install --cask font-libertinus
brew install --cask font-latin-modern
```

## License

This project is licensed under **CC BY-SA 4.0**. See [LICENSE](LICENSE) for details.