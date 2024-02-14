# Resume

> LaTeX code was generated from [resumake.io](https://resumake.io) using Template 6.

## Usage

### Building the PDF file through GitHub Actions

The PDF file is automatically generated through GitHub Actions. The `build-latex` workflow is triggered when a push is made to the `main` branch. The PDF file is then uploaded as an artifact to each workflow run.

### Building the PDF file manually

Note: You will need to have `xelatex` installed on your machine.

To generate a PDF from this LaTeX code, navigate to this folder in a terminal and run:

```sh
xelatex resume.tex
```
