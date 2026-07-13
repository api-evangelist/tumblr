---
title: "Requiring HTTPS on the Tumblr API"
url: "https://engineering.tumblr.com/post/665757792757563392"
date: "2021-10-22"
author: ""
feed_url: "https://engineering.tumblr.com/rss"
---
The time has come folks! We&rsquo;re officially dropping support for insecure (http://) requests to the Tumblr API after October 31st, 2021. Instead, please use https:// for all requests. The following day we&rsquo;ll start failing all insecure requests and invalidating any credentials sent in plain text.
