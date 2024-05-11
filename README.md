# Locales

This repository contains all locale for translating Obsidian GitHub Publisher.

> [!WARNING]
> DO NOT USE THE FILE [_model.json](_model.json).
> This file is a model and must be keeped as it is.

## Directive

- By default, the keys are automatically added when new function are added ;
- The translation is, by default, empty. You must use the english language to translate the string.
- Don't translate the `{{variable}}` used in some translation!

You can test the translation in the main plugin using the directive of developping here.

> [!NOTE]
> English is not the main language of @Lisandra-dev and some string can be inaccurate in english. If you need, you can use the french translation as a reference. If you notice some spelling mistake, the correction is also welcome!


## How to contribute

1. Fork this repository
2. Open one of the locale files 
3. Translate the file using the english file as a reference
4. Save the file
5. Create a pull request

## Adding a new translation 
- Use the file [_model.json](_model.json) as a model
- Create a new file with the name of the locale in the format `locale.json`
- Translate the file using the english file as a reference
- Save the file
- Create a pull request


The translation use [Weblate](https://weblate.org) to manage the translations. You can access the translation project [here](https://hosted.weblate.org/projects/obsidian-github-publisher/).