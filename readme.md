<img align="right" width="25%" height="25%" src=".ekznw_quarto/style/img/corplogo120.png">

# Quarto data development template

This folder contains a template Quarto document for data development for Ezemvelo KZN Wildlife Scientific Services.

> Why Quarto?
> Quarto integrates data pipelines & documentation (word, pdf, scientific manuscripts, websites). It is a leading open science tool.

# How to use

## 1. Download the data development template
**Option 1:** To download template directly from the GitHub website. Go [here](https://github.com/ekznw/quarto-data-dev) and click the green `<> code` button |> then click `Download ZIP`.       
**Option 2**:
Using git or gitbash ― `git clone https://github.com/username/repository.git`.

## 2. Edit the quarto document

Use the template to fill out metadata and data development steps.

> See the [Quarto website](https://quarto.org/) comprehensive document for technical details.
> General markdown syntax is available [here](https://www.markdownguide.org/basic-syntax/), else use a visual markdown editor like [VSCodium](https://vscodium.com/) with [Quarto extension installed](https://code.visualstudio.com/docs/configure/extensions/extension-marketplace), or [Positron](https://positron.posit.co/).

## 3. Render the Quarto document

**Option 1**: Use the shortcut to render in VSCodium `CTRL+SHFT+K` or the 'Preview' button.

**Option 2**: In the active terminal navigate to the project directory, i.e., the data_dev_template directory, and execute:     
`quarto render data_dev_vX.X.qmd`

> To render to MS Word use: `quarto render data_dev_vX.X.qmd --to docx`.        
> To render to PDF use: `quarto render data_dev_vX.X.qmd --to pdf`.
> See the [Quarto render documentation for more](https://quarto.org/docs/cli/render.html).

## Example use cases

**SANBI 2025 NBA**
- [webpage](https://nba.sanbi.org.za/contents.html)
- [github](https://github.com/SANBI-NBA)

**Australia Living Atlas**
- e.g., [their website](https://atlasoflivingaustralia.r-universe.dev/articles/delma/quick_start_guide.html)

## Resources and tutorials

**NASA Openscapes**
- [Quarto usage for science documentation](https://openscapes.github.io/quarto-website-tutorial/) ― contains links to examples of NASA Quarto websites.

**Terrestrial Science Lab**
- [Website here](https://tess-lab.org/resources/quarto/)
