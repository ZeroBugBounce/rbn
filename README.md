# rbn
Everything related to RBN

## rbn.css ##

The RBN custom css file, currently derived in small part from the [mindashq](http://www.reddit.com/r/mindashq) custom reddit theme, and the [PiNote (pinned node)](http://www.reddit.com/r/mindashq/wiki/modules/pinote) used to position the filter links directly above link content.

## subreddit_settings.sidebar.txt ##

Contains part of the sidebar code, currently only the part that will in future contain the filter links.

Note that the CSS that affects these filter links selects them based on their position.  The CSS selector:

```` .side .md > blockquote:nth-of-type(1) ````

is saying "find the 1st blockquote underneath these other selectors" and so if you modify the sidebar to have other blockquotes before this one, the CSS must also change to be able to find the right one again.