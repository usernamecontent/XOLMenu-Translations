# Translations
Translations for XOLMenu (a fork of [QOLMod](https://github.com/TheSillyDoggo/GeodeMenu/))

## File names:
File names are set to `en-US.json`, where:
`en` is a **two** letter language code, seen [here](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes)
`US` is a **two** letter region code, seen [here](https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes)

### For example
Japanese would be `ja-JP.json`

## Contributing:

### Copying base
Copy the `base.json` file from the root directory into the **langs** folder.
Change the name of this file to the **correct** region name.

### Edit the language info at the top
Change `display_name_english` to the name of the language in **english**.
Change `display_name_native` to the name of the language as written in the language.

For Japanese this would be
```json
"display_name_english": "Japanese",
"display_name_native": "にほんじん",
```

### Actual Translation
There is a section of the file called `strings`.
In this object there are the strings for the mod.
The Key (value on the left) is the text in english.
You add the translated text **after** this text.
**DO NOT MODIFY THE TEXT ON THE LEFT**

### Crediting yourself
There is a `contributors` array at the top of the file.
This is for adding credits to yourself by linking your **gd profile**.

An example credits is this:
```json
"contributors": [
    {
        "username": "TheSillyDoggo",
        "account-id": 16778880
    }
],
```

### Thank you!
Thank you for helping contribute to XOLMenu.
This means a lot and without **YOUR** help translations would not have been possible.

<3
