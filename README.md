# Standard Format
[![Build Status](https://travis-ci.org/bcomnes/sublime-standard-format.svg?branch=master)](https://travis-ci.org/bcomnes/sublime-standard-format)

A Sublime Text 3 plug-in that runs [standard-format](https://github.com/maxogden/standard-format) against the javascript code in your ST3 window on save or manually.  Can be toggled on or off.  Besides compatability details, there are no settings.

## Installation

Standard Format (the Sublime Text Plug-in) requires that you install [`standard-format`](https://github.com/maxogden/standard-format) to your global path:

```sh
$ npm install -g standard-format
```

Install Standard Format using [Package Control](https://packagecontrol.io/).

```sh
# In the command palate
- package control install
- standard format
```

## Configuration

You can find Standard Format settings in the `StandardFormat.sublime-settings` file.

- `format_on_save`: Boolean.  Runs Standard Format on save when set to true.
- `extensions`: String Array.  An array of file extensions that you want to be able to run Standard Format against.
- `loud_error`: Boolian.  Specifies if you get a status bar message or error window if the subprocess encounters an error while formatting.
