# Use of the NeurIPS format template

This is a [Quarto-based](https://quarto.org) template that assists you in creating a manuscript for Computo.

## Creating a new article

You can use this as a template to create an article for Computo. To do this, use the following command:

```bash
quarto use template stevengogogo/neurips-quarto-extension
```

This will install the extension and create an example qmd file and bibiography that you can use as a starting place for your article.

## Installation for existing document

You may also use this format with an existing Quarto project or document. From the quarto project or document directory, run the following command to install this format:

```bash
quarto add stevengogogo/neurips-quarto-extension
```

## Usage

To use the format, you can use the format names `computo-html`. For example:

```bash
quarto render article.qmd --to neurips-html
```

or in your document yaml

```yaml
format:
  neurips-html: default
```

You can view a preview of the rendered HTML and PDF template at <https://computorg.github.io/computo-quarto-extension/> (for PDF, see "other formats" bnext to the TOC).


## Example

- PDF output is at https://stevengogogo.github.io/neurips-quarto-extension/template.pdf
- HTML: https://stevengogogo.github.io/neurips-quarto-extension/