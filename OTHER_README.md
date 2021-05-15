# Explainer

In which I introduce you to strange words and the **IndieWeb!** ヽ(‘ ∇‘ )ノ

## What is the IndieWeb?

The Independent Web is the good part of the Internet, made up of thoughtful folks who wanted **ownership and independence** of their thoughts. Instead of giving away these ideas for free to benefit any company's website, the people of the IndieWeb built their own websites!

IndieWeb isn't a particular platform or social media site. It's a paradigm shift that's as old as the Internet, and at the same time, a fresh new way of thinking about your identity online. The core tenant is just this:

**Make your own website.**

## How do I join?

The first step is to make your own website! (IndieFeed wants to help you with that. .=^.^=)

**Your website is your identity on the web.** Accounts and data at other websites that you don't own are subject to their whims and can be removed, exploited, or cancelled — but your website is fully under your control! If you have the site files, you can move it and host it wherever you like. (ﾉﾟ▽ﾟ)ﾉ

There's no "one way to do things." Instead, there are some standards and specifications that describe how different independent websites can talk to and interact with each other.

### microformats2

[**microformats2**](https://microformats.org/wiki/microformats2) refers to a type of markup that helps [readers](https://indieweb.org/reader) parse an IndieWeb page. This allows readers to show you information like the author of a website, or a stream or feed of their latest posts!

IndieFeed is already set up with microformats2, so you don't need to worry! ＼(^-^)／

### Webmention

[**Webmentions**](https://www.w3.org/TR/webmention/) help one website talk to another website through a notification that links one URL to another. It's like a comment system that works across websites, no matter where or how they're hosted!

Learn more about [Webmention at the IndieWebCamp wiki](https://indieweb.org/Webmention).

IndieFeed contains [a JavaScript function](./static/js/wm.js) that fetches and displays your Webmentions if you're using [Webmention.io](https://webmention.io/). You can modify the script to work with other Webmention services as well, or even with your own server!

### POSSE and Bridgy

**POSSE** is an acronym for ***P**ublish (on your) **O**wn **S**ite, **S**yndicate **E**lsewhere*. [**Bridgy**](https://brid.gy/) is a hosted service that makes it easy to POSSE to some different social networks.

This concept makes it easy to share your thoughts to many social media silos like Twitter or Medium, or even other platforms like Mastodon — all by just posting in one place: your own website!

You can learn more about the practice of [POSSE on the IndieWebCamp wiki](https://indieweb.org/POSSE).

### IndieAuth

Because your website is your identity, [**IndieAuth**](https://indieauth.net/) helps you use your own domain to sign into supported services using OAuth. It works with the services mentioned above, like Webmention.io, Bridgy, and much more!

IndieFeed has IndieAuth set up for you already! ヘ( ^o^)ノ＼(^_^ ) Just don't forget to edit your configuration file!

## How do I get help?

Don't worry! (∩^o^)⊃━☆ﾟ.*･｡ﾟ The IndieWeb community has lots of nice folks and you can ask for help anytime! You can use `#indieweb` just about anywhere, but here are a few places that a lot of us hang out:

- Mastodon (try fosstodon.org and use `#indieweb`)
- The [IndieWebCamp chat](https://indieweb.org/discuss) (IRC with bridges to Slack, Matrix, and more!)
- Virtual and in-person [events organized by IndieWebCamp](https://events.indieweb.org/)

## Okay! Let's start!

I hope this helps explain things so you can start creating your own independent website! You can start using IndieFeed by following the steps in the [README.](README.md)

〜(￣▽￣〜)(〜￣▽￣)〜
