# Slightly better blog

This blog has 100 posts with 100 comments each and 100 replies to those. To make this Rails blog bearable to load, the index page was changed to show only the posts, comments and replies are shown on individual post pages, and page caching was added to save static pages and serve them up instead of going back to the database each time.

## Performace of the Heroku deployment

[LoadImpact](http://loadimpact.com/test/view/1599385)

note that the deployment will be deleted within the week to not lock up Postgresql access of a free Heroku account
