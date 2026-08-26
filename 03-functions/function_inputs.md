---
type: action
inputs:
  - first_name
  - last_name
source_facet: description
description_hash: cdd03a999238e0d8c89019ed2cde50be4f4059475b7bb0abbb01b2fdeb337879
recipe_hash: 0984b7a60d86eb5b59b2968af78cf7343520f11ba71070ced04e187c800e380a
python_hash: e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
recipe_derived_from_description_hash: cdd03a999238e0d8c89019ed2cde50be4f4059475b7bb0abbb01b2fdeb337879
recipe_derived_from_source_hash: cdd03a999238e0d8c89019ed2cde50be4f4059475b7bb0abbb01b2fdeb337879
python_derived_from_recipe_hash: e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
python_derived_from_source_hash: cdd03a999238e0d8c89019ed2cde50be4f4059475b7bb0abbb01b2fdeb337879
recipe_version: 1
---

# Description

Chapter 3 — a function can take more than one input. Joins a first and last name.

## Inputs

- first_name — a given name
- last_name — a family name

# Recipe

Input first_name: str = "Ada".
Input last_name: str = "Lovelace".
Return first_name + " " + last_name.
