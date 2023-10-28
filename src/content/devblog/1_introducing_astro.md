---
title: Astro framework
tags: ["frontend", "blogs", "learning"]
date: 2023-10-28
---

Today I attened the JavaScript Edinburgh meetup code jam session, my first tech meetup since moving to Bonnie Scotland less than 2 weeks ago.

It has been a while since I tinkered with any front end technology but it didn't take long to get those brain cells remembering the React and TypeScript nuances.

When creating the content collection, if `astro:content` can not be found, run `npx astro sync` on the command line. This will create a `src/env.d.ts` file which references the astro content, thus the error should resolve.
