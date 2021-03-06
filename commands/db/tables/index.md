---
layout: default
title: 'wp db tables'
---

`wp db tables` - List the database tables.

### OPTIONS

[\--scope=&lt;scope&gt;]
: Can be all, global, ms_global, blog, or old tables. Defaults to all.

### EXAMPLES

    # Export only tables for a single site
    wp db export --tables=$(wp db tables --url=sub.example.com | tr '\n' ',')

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



