---
layout: post
title: "Getting Started With Jekyll!"
date: 2025-05-08 12:58:29 +0100
categories: jideotetic-blog posts
---

Jekyll is a static site generator. It takes text written in your favorite markup language and uses layouts to create a static website. You can tweak the site’s look and feel, URLs, the data displayed on the page, and more [jekyll.com][jekyll].

## Prerequisites

Jekyll requires the following:

- Ruby version 2.7.0 or higher
- RubyGems
- GCC and Make

## Instructions

1. Install all prerequisites.

2. Install the jekyll and bundler gems.

   ```
   gem install jekyll bundler
   ```

3. Create a new Jekyll site at ./myblog.

   ```
   jekyll new myblog
   ```

4. Change into your new directory.

   ```
   cd myblog
   ```

5. Build the site and make it available on a local server.

   ```
   bundle exec jekyll serve
   ```

6. Browse to http://localhost:4000

[jekyll]: https://jekyllrb.com/docs/
