---
layout: default
title: 'wp core language list'
---

`wp core language list` - List all languages available.

[\--field=&lt;field&gt;]
: Display the value of a single field

[\--&lt;field&gt;=&lt;value&gt;]
: Filter results by key=value pairs.

[\--fields=&lt;fields&gt;]
: Limit the output to specific fields.

[\--format=&lt;format&gt;]
: Accepted values: table, csv, json. Default: table

### AVAILABLE FIELDS

These fields will be displayed by default for each translation:

* language
* english_name
* native_name
* status
* update
* updated

These fields are optionally available:

* version
* package

### GLOBAL PARAMETERS

  \--path=&lt;path&gt;
      Path to the WordPress files

  \--url=&lt;url&gt;
      Pretend request came from given URL. In multisite, this argument is how the target site is specified.

  \--user=&lt;id|login|email&gt;
      Set the WordPress user

  \--skip-plugins[=&lt;plugin&gt;]
      Skip loading all or some plugins

  \--skip-themes[=&lt;theme&gt;]
      Skip loading all or some themes

  \--require=&lt;path&gt;
      Load PHP file before running the command (may be used more than once)

  \--[no-]color
      Whether to colorize the output

  \--debug
      Show all PHP errors

  \--prompt
      Prompt the user to enter values for all command arguments

  \--quiet
      Suppress informational messages



