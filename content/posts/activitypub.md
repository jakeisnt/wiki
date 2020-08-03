+++
title = "ActivityPub"
author = ["Jacob Chvatal"]
lastmod = 2020-08-01T23:33:04-07:00
slug = "activitypub"
draft = false
+++

<https://raw.githubusercontent.com/w3c/activitypub/gh-pages/activitypub-tutorial.txt>
how the protocol works
<https://gohugo.io/> to use
<https://orgmode.org/manual/Handling-Links.html> handling external links with
org
<https://willschenk.com/articles/2019/using%5Forg%5Fmode%5Fin%5Fhugo/> helpful emacs org mode tweaks


## activitypub research {#activitypub-research}

i believe that using this protocol is the best

1.  host local servers, one tracking each service
2.  connect to these servers with a locally hosted mastodon client
3.  each server takes account information and mocks external accounts:
    -   logs in through social media api
    -   view posts, corresponding threads/comments sections
    -   server publishes data form these services in real time to mastodon
    -   server creates/tracks fake mastodon user from every other user
    -   these users are visible with clever naming scheme and tolerated by
        server
    -   interacting with these real servers from ur acct (must be hosted in same
        place) == ur account on that social media interacting with their real
        acct
    -   likes, follows etc. also emulated -- though have to check if current
        user is following them, has liked, has followed etc.

    -   should port over images, videos, gifs etc from whatever proprietary
        twitter thing they use to sane default formats to display on mastodon
        (i guess these should be cached for some time period, then...)

[federated social media is the future.](https://pleroma.tilde.zone/main/all)