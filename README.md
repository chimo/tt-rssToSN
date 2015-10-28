# Intro

**2012/02/23 Update:** There is an [offical plugin](https://tt-rss.org/gitlab/fox/tt-rss-attic/tree/master/plugins/identica) for this that uses the "Bookmark" StatusNet feature (instead of a regular notice).

A "[Tiny Tiny RSS](http://tt-rss.org)" plugin that adds the ability to share a link from tt-rss to a StatusNet instance (such as [identica](http://identi.ca)):

![Screenshot](http://chromic.org/images/ttrss2sn.png)

# Install

1. Copy the contents of this project into your tt-rss installation.
1. **(optional)** If you're using your own StatusNet instance, change "identi.ca" to your instance's location in **/js/sn_button.js** on line 18.
1. In your TT-RSS config.php, around line 194 where it says "ARTICLE_BUTTON_PLUGINS", add "sn" to the list. Example: define('ARTICLE_BUTTON_PLUGINS', 'note,tweet,share,mail,sn');
1. Reload or visit your Tiny Tiny RSS instance and you should have a "Share to StatusNet" button.

# Flattr this Project
[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=chimo&url=https://github.com/chimo/tt-rssToSN&title=Share to StatusNet from Tiny Tiny RSS&language=&tags=github&category=software)
