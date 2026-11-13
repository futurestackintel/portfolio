---
layout: ../../layouts/PostLayout.astro
title: "What I learned building this portfolio"
date: "2026-11-11"
summary: "Three small bugs, three real lessons."
---

I'm learning full stack while building this site, and a few small bugs taught me more than any tutorial.

## An import doesn't put anything on the page

I imported a component and nothing showed up. The import only tells the file the component exists. You still have to place its tag where you want it to appear.

## Never trust the browser

Anything running in a visitor's browser can be read or changed by them. That's why anything that matters, like checking an answer, has to be verified on a server.

## Scripts can be blocked on purpose

PowerShell refused to run `npm` until I changed its execution policy. The default is strict for a reason, so I loosened it only for my own user and only as far as I needed.
