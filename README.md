<a href="https://freesewing.org/"><img src="https://freesewing.org/img/logo/logo-black.svg" align="right" width=200 style="max-width: 20%;" /></a>

# Freesewing i18n (internationalisation)

[Freesewing](https://freesewing.org/) is an online platform to draft sewing patterns based on your measurements.

> This is the i18n repository, which holds our internationalisation efforts.

This repository holds translated strings for [freesewing](https://freesewing.org).

This is in preparation of our new frontend which will be multilingual.

There are 3 files that need translating:

 - `measurements.yaml` contains the names and description of body measurements
 - `patterns.yaml` contains the names and description of our patterns
 - `options.yaml` contains the names and descriptions of all pattern options

## How to help with translating

You have the choice between joining an effort for a language that's already here, 
or starting on a new language.

### Adding a new language

Every language should be in its own folder, named according to 
the lowercase [ISO 639-1 language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes).  
For example, `en` for English.

To start working on a new language, copy the `xx` template folder. 

For example, copy the entire `xx` folder as a new folder called `pl` if you want to work on Polish.

### Working on an existing language

If the folder for the language you want to work on is already there, you are good to go.

## Keeping track of your work with the `# TODO` comments

In the best case scenario, you don't have to do an entire language on your own, and others can help.

To make that somewhat simpler, every line that needs translating has a `# todo` comment at the end of it.
When you're done translating a line, simply remove the `# TODO` comment to indicate the line is translated.

This allows other people to quickly skim a file for any remaining work. 
It also allows us to check automatically how much translation work is done for a given language.

## Working with GitHub

You'll need a GitHub account to make changes here. No worries, they are free.

If you're familiar with git/GitHub, you can fork the repository, and submit a pull request.
If you like, we can give you write access to the repository so you can commit your changes directly. 
Get in touch (see below) if you'd like that.

If not, you can simply make the changes through the GitHub repository:

 - Navigate to the file you want to edit, and click the pencil icon
 - Make your changes, and add a little message at the bottom under **Propose file change**
 - Then, click the **Propose file change** button to submit your work

## Translation tips

 - Try to be consistent with punctuation. Typipcally titles don't have a full stop, whereas descriptions do
 - Translate as you wish, but keep the (short) pattern names the same. Don't change `Simon` into `Bernard`, but feel free to translate `Simon Shirt` as `Chemise Simon`.
 - When translating options, the [freesewing website](https://freesewing.org) has them all explained in case you need context.

## Questions / Suggestions / Coordination

There's a dedicated [i18n chatroom on Gitter](https://gitter.im/freesewing/i18n)
for all translators and questions related to internationalisation.

Let's meet there 😃
