# We are twtxt

Twtxt is decentralised, minimalist microblogging service. Head over
to https://github.com/buckket/twtxt if you want to know more. It's
hard to find users you can subscribe to, so this list helps you to get
started. There are not bots on this list, just real people (or dogs). Most
urls are not active anymore but some of us still post regularily. Let
me know if you want to be added.

## How to import the list

    xargs -n2 twtxt follow < we-are-twtxt.txt

## Files

  - `we-are-twtxt.txt` list of active twtxt users with working links
  - `we-were-twtxt.txt` users with links that haven't been working for awhile
  - `we-are-bots.txt` list of bots

## Other lists

@prologic runs the [rss2twtxt](https://feeds.twtxt.net/) service that lets
you read RSS/Atom feeds in you twtxt client. The service exposes a list over
currently known feeds at

    https://feeds.twtxt.net/we-are-feeds.txt

You can download the file and add interesting feeds manually, or you can add
the whole shebang with

```sh
    $ curl -s https://feeds.twtxt.net/we-are-feeds.txt |\
          xargs -n2 twtxt follow
```
