---
title: Portfolio
layout: default
---

## Portfolio

### News Slackbot

| [derekmfrank.com/newsbot][newsbot-website] | 2017 | [GitHub Repository][newsbot-repo] |

![Newsbot example][newsbot-img]

#### Description

A Slackbot that fetches news articles and delivers them to any number of Slack
channels that the bot is subscribed to.

Currently only Twitter is used to fetch articles, but the bot was designed to allow
new clients to be plugged in easily.

#### Technology
* [Python 3.6][python3.6]
* [Docker][docker]
* [Slack RTM API][slack-rtm-api]


----
### Personal Website

| [derekmfrank.com][personal-website] | 2017 | [GitHub Repository][personal-website-repo] |

#### Description

Incorporated CDN, [Cloudflare][cloudflare], to reduce load, improve
response times, and freely serve over HTTPS.

Chose complimentary color palette.  Creatively styled call-to-actions
so as not to conflict with color palette and chosen font weights.

#### Technology
* [GitHub Pages][gh-pages]
* [Jekyll][jekyll]
* [Cloudflare][cloudflare]


----
### Link Crawler

| 2015 | [GitHub Repository][link-crawler-repo] |

#### Description

A crawler to count links of a specific type.  The goal was to be able
to determine how many PDFs were hosted on a given domain.

#### Technology
* [Python 2.7][python2.7]
* [Scrapy][scrapy]


----
### Old Personal Website

| 2013 | [GitHub Repository][old-personal-website-repo] |

#### Description

First personal website deployed with a shared virtual server.

#### Technology
* [Python 2.6][python2.6]
* [Django 1.7][django1.5]
* [SQLite 3][sqlite3]
* [Apache 2][apache2]
* [DreamHost][dreamhost]




[newsbot-repo]: {{ site.github.owner_url }}/newsbot
[newsbot-website]: /newsbot/
[newsbot-img]: /assets/img/newsbot-example.png "Newsbot example"

[personal-website-repo]: {{ site.github.repository_url }}
[personal-website]: /

[link-crawler-repo]: {{ site.github.owner_url }}/LinkCrawler
[link-crawler-website]: #

[old-personal-website-repo]: {{ site.github.owner_url }}/old-personal-website
[old-personal-website]: #

[python3.6]: https://docs.python.org/3.6/
[python2.7]: https://docs.python.org/2.7/
[python2.6]: https://docs.python.org/2.6/
[scrapy]: https://scrapy.org/
[django1.5]: https://www.djangoproject.com/
[sqlite3]: http://sqlite.com/
[apache2]: https://httpd.apache.org/docs/
[jekyll]: https://jekyllrb.com/
[docker]: https://docs.docker.com/
[slack-rtm-api]: https://api.slack.com/rtm
[gh-pages]: https://pages.github.com
[cloudflare]: https://www.cloudflare.com/
[dreamhost]: https://www.dreamhost.com/
