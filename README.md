# Freesewing strings

This repository holds translated strings for [freesewing](https://freesewing.org).

This is in preparation of our new frontend which will be multilingual.

There are 3 files that need translating:

 - `measurements.yaml` contains the names and description of body measurements
 - `patterns.yaml` contains the names and description of our patterns
 - `options.yaml` contains the names and descriptions of all pattern options

## How to help with translating

Every language should be in its own folder, named according to 
the lowercase [ISO 639-1 language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes).  
For example, `en` for English.

If the folder of your language already exists, you can work on the files in that folder.

If it does not exist, you can copy the `xx` template folder to a new folder. 
For example, copy the entire `xx` folder as a new folder called `pl` if you want to work on Polish.

## Keeping track of your work

In the best case scenario, you don't have to do an entire language on your own, and others can help.

To make that somewhat simpler, every line that needs translating has a `# todo` comment at the end of it.
When you're done translating a line, simply remove the `# TODO` comment to indicate the line is translated.

This allows other people to quickly skim a file for any remaining work. 
It also allows us to check automatically how much translation work is done for a given language.

## Questions / Suggestions / Coordination

There's a dedicated [i18n chatroom on Gitter](https://gitter.im/freesewing/i18n)
for all translators and questions related to internationalisation.


