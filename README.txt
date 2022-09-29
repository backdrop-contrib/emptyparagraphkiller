Empty paragraph killer - sometimes users are overzealous with the
carriage return

-- SUMMARY --

Empty paragraph killer is a filter module. It is helpful on sites that use
WYSIWYG editors. People often hit the return key twice at the end of a
paragraph, resulting in an empty paragraph (<p></p> or <p>&nbsp;</p>) when the
content is viewed. This module removes that sort of paragraph.

-- INSTALLATION --

* Install as usual.

-- CONFIGURATION --

* Go to your input formats (/admin/config/content/formats)
* Click the configure link next to the desired input format.
* Click the checkbox next to 'Empty paragraph filter'.
* Move 'Empty paragraph filter' to the bottom bottom of the filter list, unless
  you know there are other filters that need to be processed after it.

-- CONTACT --

Ported to Backdrop by:
* Mark Burgess (markabur) - https://github.com/markabur/

Drupal version created & maintained by:
* Richard Sheppard (siliconmeadow) - http://drupal.org/user/55284

Sponsored by:
* Aroq Ltd - an online publisher providing authoritative and timely
  global business information for busy executives via four dedicated
  industry specific websites: http://www.just-auto.com,
  http://www.just-style.com, http://www.just-food.com &
  http://www.just-drinks.com, all of which are in the process of being
  converted to Drupal.

-- LICENSE --

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
