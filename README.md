# Tachyons Extension For Quarto

![GitHub Action Status](https://img.shields.io/github/actions/workflow/status/nareal/tachyons/publish.yml)

This extension adds the [TACHYONS - Css Toolkit](http://tachyons.io/) to a quarto HTML document or quarto revealjs presentation. 

> Functional CSS for humans.
> Quickly build and design new UI without writing CSS.

It allows changing the design of HTML elements by adding classes to them.

## Installing


If you want to start with a template do:
```bash
quarto use template nareal/tachyons
```


You just want to install the extension use:

```bash
quarto add nareal/tachyons
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.


To update the extension use:

```bash
quarto update extension nareal/tachyons
```

and to remove it:

```bash
quarto remove extension nareal/tachyons
```

## Using

To use the extension simply add it as a filter to the YAML header of the quarto document, for example:

```
---
title: "Tachyons Example"
filters:
  - tachyons
---
```

You can now use the library by adding its classes to the HTML elements.

To learn more:

- [tachyons tldr](https://tachyons-tldr.vercel.app/#/classes)
- [dwyl/learn-tachyons: Learn how to use Tachyons to craft beautiful, responsive and fast UI with functional CSS!](https://github.com/dwyl/learn-tachyons)


## Example

Here is the source code for a minimal example: [example.qmd](example.qmd), and the resulting [rendered HTML file](https://nareal.github.io/tachyons/).

