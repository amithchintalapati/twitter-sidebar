# twitter-sidebar
Adds a Twitter Sidebar to the Discourse discovery/topics.hbs

To get it to load your twitter feed instead of Discourse's, you need to follow the instruction on line 30 in Desktop head_tag.html and add the correct code on line 39.

If you have  Content-Security-Policy Enabled, you need to add these lines to your Settings > Security > content security policy script src:
https://platform.twitter.com
https://cdn.syndication.twimg.com
