# Cookbook

A LaTeX class for formatting recipes.

## Requirements

* LaTeX >= 2e
* The following LaTeX packages
  * enumitem
  * lettrine
  * etoolbox
  * kvoptions
  * xifthen
  * xcolor
  * cooking-units

## Usage

### Package options

* color
* toc
* recipelevel

### Recipe environment

* info macro
  * serves macro
  * makes macro
  * preptime macro
  * cooktime macro
* intro macro
* ingredients macro
  * component macro
  * ingredientslist macro (provide a comma separated list)
* method macro
  * step macro (lettrine)
* hint macro

## Inspiration

* xcookybooky Sven Harder https://ctan.org/pkg/xcookybooky
* cuisine Ben Cohen https://ctan.org/pkg/cuisine
