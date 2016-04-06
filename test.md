Package Control Messages 
========================

CSS3
----

  VERSION 1.3.2 CHANGES
  
  1) The url() rule now only highlights quoted URLs. Unquoted URLs are not
     illegal in CSS, but they are discouraged by the spec as legacy code. Unquoted
     URLs have to be specially parsed, have more characters that need to be
     escaped, and do not support URL modifiers. Please update your code.
  
         https://drafts.csswg.org/css-values/#urls
  
  2) Fixed translate*() rule not matching percentages.

  VERSION 1.3.0 CHANGES
  
  1) full SVG2 support
  2) HTML5.1 element selectors
  3) update for latest Media Queries Level 4 draft
  4) update for CSSOM View Model spec
  
  This is a big update! There are lots of new highlighting rules and completions.
  If you see anything that looks wrong, please open an issue here:
  
    https://github.com/y0ssar1an/CSS3/issues
  
  Thanks very much!

  VERSION 1.2.16 CHANGES
  
  1) Support user-select, since it's now on the standards track.
  2) Update for the latest changes to the CSS Basic User Interface Module
     Level 4 spec.
  3) The install notes describe how to disable Emmet CSS completions
     by adding these lines to the Emmet package settings:
  
      "show_css_completions": false,
      "disable_tab_abbreviations_for_scopes": "source.css"
  
     Thank you mohamadnorouzi20 for pointing this out!
