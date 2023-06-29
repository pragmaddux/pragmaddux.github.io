---
layout: post
title:  "Wrestling with Style"
date:   2023-06-26 21:47:54 -0500
categories: blog
---

After a morning of wrestling with Jekyll themes, skins and custom CSS, I'm finally confortable with the customization level
I wanted with this blog. I've discovered a few things:

- Jekyll theming doesn't always play nicely with GitHub Pages thanks to the version mismatches
- You usually have to select the pre-made Jekyll theme much earlier in the build process (leading me to stick with just using the default Minima theme with custom CSS)
- The "skins" feature of the Minima theme arrived with Minima v3.0, and the default will load v2.5.1

All said and done, you should follow [this readme to overload custom CSS on Minima v2.5](https://github.com/jekyll/minima/tree/2.5-stable) on a similar default Jekyll build for GitHub.
While it was a bit more work than I expected, it was a nice learning experience that will let me be a bit more hands-on with the blog layout. And with a little CSS tweaking,
I finally have a "dark theme" on this blog, which is what I was going for.