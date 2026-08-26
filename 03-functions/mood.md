---
type: action
inputs: [style]
source_facet: description
description_hash: 7bfe68af573df78f253bf85222c95fd73cc1e6c9f7f7677b5b6f5b6aca6188c6
recipe_hash: 88d9f9076020b3f3afc8c37a6ab5365ae3438c9a350c73a2d351e2eb0033a84b
python_hash: a7d3126f12c2e52d72b0fc2a0027b17e7e9872165d6ddd69d123f27244ed2dbb
recipe_derived_from_description_hash: 7bfe68af573df78f253bf85222c95fd73cc1e6c9f7f7677b5b6f5b6aca6188c6
recipe_derived_from_source_hash: 7bfe68af573df78f253bf85222c95fd73cc1e6c9f7f7677b5b6f5b6aca6188c6
python_derived_from_recipe_hash: b021764a6c06e758d387cc0a04ac066a505e9df78208506553758e0ded32e85e
python_derived_from_source_hash: 7bfe68af573df78f253bf85222c95fd73cc1e6c9f7f7677b5b6f5b6aca6188c6
recipe_version: 2
---

# Description

Chapter 3 — an input with a fixed set of choices shows up as a dropdown instead of a text box. Pick a style and get a greeting in that voice.

## Inputs

- style — one of "cheerful", "formal", "sleepy"

# Recipe
Input style: 'cheerful' | 'formal' | 'sleepy' = "cheerful".
If style == "cheerful":
  Return "Hey hey hey!!!".
If style == "formal":
  Return "Good day to you.".
Return "...zzz...".

# Python

```python
def compute(context, style: str = 'cheerful'):
  if (style == 'cheerful'):
    return 'Hey hey hey!!!'
  if (style == 'formal'):
    return 'Good day to you.'
  return '...zzz...'

```
