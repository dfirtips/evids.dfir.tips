---
layout: page
title: Contribute
---

## Structure

Each artifact is defined in a file in the [`_evids/`] folder named as `<artifact>.md`, such file consists only of a [YAML] front matter which describes the binary and its functions.

The full syntax is the following:

```
---
title: Title of the artifact entry
description: |
    Multiline description
location: |
    Multiline location
interpretation: |
    Multiline intepretation
evids-categories:
    - CATEGORY
---
```

Where `CATEGORY` is one of the values described in the [`_data/evids-categories.yml`] file.

Feel free to use any file in the [`_evids/`] folder as an example.

## Pull request process

There are no upfront requirements of what new entry should or should not be about. Each pull request will be evaluated individually.

Pull requests adding new functions in [`_data/evids-categories.yml`] are allowed and subjected to project maintainers vetting.

[YAML]: http://yaml.org/
[`_evids/`]: https://github.com/dfirtips/evids.dfir.tips/blob/master/_evids/
[`_data/evids-categories.yml`]: https://github.com/dfirtips/evids.dfir.tips/blob/master/_data/evids-categories.yml
