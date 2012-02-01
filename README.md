# Intro

A "[Tiny Tiny RSS](http://tt-rss.org)" plugin that adds the ability to share a link from tt-rss to a StatusNet instance (such as [identica](http://identi.ca)):

![Screenshot](http://chromic.org/images/ttrss2sn.png)

# Install

1. Copy the contents of this project into your tt-rss installation.
1. **(optional)** If you're using your own StatusNet instance, change "identi.ca" to your instance's location in **/js/sn_button.js** on line 18.
1. In your TT-RSS config.php, around line 194 where it says "ARTICLE_BUTTON_PLUGINS", add "sn" to the list. Example: define('ARTICLE_BUTTON_PLUGINS', 'note,tweet,share,mail,sn');
1. Reload or visit your Tiny Tiny RSS instance and you should have a "Share to StatusNet" button.
