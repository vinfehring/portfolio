---
title: "Working with Legacy Code"
pubDate: 2024-06-17
description: "How I landed myself into working with Legacy Code on a daily basis."
author: "Vin"
tags:
  [
    "asp classing",
    "typescript",
    "go",
    "supabase",
    "postgres",
    "react",
    "vendtrak",
    "saas",
  ]
---

# Working with Legacy Code

_Jun 27, 2024_

Working with a legacy app has never been my goal in life... Though, when it happened, I needed to really re-evaluate things. Did I want to maintain code that was written in ASP Classic? Or did I want to just dive straight in, head first, and do a complete rewrite into something more modern? Well, the choice was a lot more difficult than I ever imagines it would be. Not only did I need to maintain the old code (so that users of the application didn't get mad about it breaking down), but then I had to maintain a completely separate repository of code that was something modern. The only choice I needed to make was what was that something more "modern".

I tossed around a few ideas. I was going to use what I knew best... I was going to use PHP. Then, it started to dawn on me, that the world was shifting away from PHP to things more aligned for speed and simplicity, like JavaScript (or better yet, TypeScript). So, I decided that should be the route that I go... Well, then a developer friend of mine pestered me into learning Go. This changed the way I thought about everything now, as I could write some serious code, super fast. But, did I want to use any of these? Not really, as they were not my main development languages. Long story short, I decided to go with a Go backend API, and a TypeScript/React frontend using NextJS.

We are now 4 years later, after the decision to make the rewrite happen, I'm still managing the classic ASP code, which is slowly going the way of the dodo bird, but it is what keeps the business running while I tinker around with bringing the rewrite up to feature parity. There will definitely be more write-ups about this as the process continues.
