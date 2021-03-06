---
layout: default
title: 'wp theme disable'
---

`wp theme disable` - Disable a theme in a multisite install.

### OPTIONS

&lt;theme&gt;
: The theme to disable.

[\--network]
: If set, the theme is disabled on the network level. Note that
individual sites may still have this theme enabled if it was
enabled for them independently.

### EXAMPLES

    wp theme disable twentythirteen

    wp theme disable twentythirteen --network

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



