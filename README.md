# Resume

> The initial LaTeX code was generated from [resumake.io](https://resumake.io)
> using Template 6, and then modified to fit my needs.

## Usage

### Building the PDF file through GitHub Actions

The PDF file is automatically generated through GitHub Actions.
On `main` branch pushes, `build-latex` workflow is triggered, `resume.tex` is compiled,
and the PDF file is uploaded as an artifact to each workflow run.

### Building the PDF file manually

Note: You will need to have `xelatex` installed on your machine.

To generate a PDF from this LaTeX code,
navigate to this folder in a terminal and run:

```sh
xelatex resume.tex
```
