---
layout: default
title: 'wp plugin list'
---

`wp plugin list` - Get a list of plugins.

### OPTIONS

[\--&lt;field&gt;=&lt;value&gt;]
: Filter results based on the value of a field.

[\--field=&lt;field&gt;]
: Prints the value of a single field for each plugin.

[\--fields=&lt;fields&gt;]
: Limit the output to specific object fields.

[\--format=&lt;format&gt;]
: Accepted values: table, csv, json, count. Default: table

### AVAILABLE FIELDS

These fields will be displayed by default for each plugin:

* name
* status
* update
* version

These fields are optionally available:

* update_version
* update_package
* update_id
* title
* description

### EXAMPLES

    wp plugin list --status=active --format=json

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



