
# ION Navigation Journal template

This is a quarto extension for the [Institute of Navigation's (ION)](https://www.ion.org) journal [Navigation](https://www.ion.org/navi/submit-navi.cfm). It uses version 2 of the IONconf class (`IONconf-v2.cls`), downloaded [here](https://www.ion.org/navi/submit-navi.cfm) on 2023-11-14.

There is also an older version (v1?) that is linked to some conference proceedings, `IONconf.cls`.

Zip files of both original templates can be found in the `_external` directory as
- `ionconf-v1-latex-template.zip`, downloaded 2023-11-14
- `ionconf-v2-latex-template.zip`, downloaded 2023-11-14

## Creating a New Article

To create a new article using this format:


```bash
quarto use template anielsen001/ionnavi
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:


```bash
quarto add anielsen001/ionnavi
```

Then, add the format to your document options:

```yaml
format:
  ionnavi-pdf: default
```    

## Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

