---
layout: default
title: 'wp menu item add-term'
---

`wp menu item add-term` - Add a taxonomy term as a menu item

&lt;menu&gt;
: The name, slug, or term ID for the menu

&lt;taxonomy&gt;
: Taxonomy of the term to be added

&lt;term-id&gt;
: Term ID of the term to be added

[\--title=&lt;title&gt;]
: Set a custom title for the menu item

[\--link=&lt;link&gt;]
: Set a custom url for the menu item

[\--description=&lt;description&gt;]
: Set a custom description for the menu item

[\--attr-title=&lt;attr-title&gt;]
: Set a custom title attribute for the menu item

[\--target=&lt;target&gt;]
: Set a custom link target for the menu item

[\--classes=&lt;classes&gt;]
: Set a custom link classes for the menu item

[\--position=&lt;position&gt;]
: Specify the position of this menu item.

[\--parent-id=&lt;parent-id&gt;]
: Make this menu item a child of another menu item

[\--porcelain]
: Output just the new menu item id.

### EXAMPLES

    wp menu item add-term sidebar-menu post_tag 24

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



