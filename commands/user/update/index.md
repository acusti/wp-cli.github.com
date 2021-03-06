---
layout: default
title: 'wp user update'
---

`wp user update` - Update a user.

### OPTIONS

&lt;user&gt;...
: The user login, user email or user ID of the user(s) to update.

\--&lt;field&gt;=&lt;value&gt;
: One or more fields to update. For accepted fields, see wp_update_user().

### EXAMPLES

    wp user update 123 --display_name=Mary --user_pass=marypass

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



