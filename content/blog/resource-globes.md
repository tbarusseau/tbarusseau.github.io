+++
title = "Pretty resource bubbles"
date = 2022-09-09
draft = true

[taxonomies]
categories = ["Graphics programming"]
tags = ["shaders", "graphics-programming"]

[extra]
lang = "en"
toc = true
show_comment = true
math = false
mermaid = false
cc_license = true
outdate_warn = true
outdate_warn_days = 120
+++

# Pretty bubbles

Action-RPG games like [Path of Exile][1] or [Diablo][2] usually feature resources for you character, such as life or mana.

[1]: https://pathofexile.com
[2]: https://diablo2.blizzard.com/

On top of being informative at a glance, they can be really pretty:

![img](/img/resource-bubbles/poe-health.png)

They usually feature moving textures, for example in Diablo 3:

![img](/img/resource-bubbles/diablo-3.gif)

But... How can I do something similar?

## What we're gonna use

- A Unity project with the built-in renderer
- Some pretty textures
- Shader and mesh magic ✨

## What this post won't cover

- Actually drawing a pretty UI around the bubble because I can't draw.

# Getting started
