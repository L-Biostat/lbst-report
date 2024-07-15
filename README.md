# L-Biostat statistical report in R <img align="right" height="100" src="https://ibiostat.be/images/IBiostat-logo.png/@@images/image/preview">

Quarto extension for a template to generate a PDF (or an html file) for a 
statistical report for a L-Biostat project using R.

## Installation and use

To install the Quarto extension, create a directory, and use the template file:

``` bash
quarto use template L-Biostat/lbst-report
```

To use the extension in an existing project without installing the template 
file:

``` bash
quarto install extension L-Biostat/lbst-report
```

To use the template in a project, simply use

``` yaml
format:
  pdf: lbst-report
```

for pdf outputs, or 

``` yaml
format:
  html: lbst-report
```

for html outputs, in the `yaml` header of your main quarto file.

## Example

Here is the source code for a minimal sample document: 
[template.qmd](template.qmd).