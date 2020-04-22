# Standard

This directory contains editorial material for managing the standard document.

## Generating HTML and PDF

To generate HTML and PDF representations of the standard, [Ruby](https://www.ruby-lang.org/en/downloads)
and [asciidoctor](https://asciidoctor.org) are required.  Once Ruby is installed, run the following commands
for asciidoctor support:

```bash
gem install asciidoctor --pre
gem install asciidoctor-pdf --pre
```

From here, run `HTML_gen.bat` and `PDF_gen.bat` accordingly.  Outputs are written to the parent directory.
