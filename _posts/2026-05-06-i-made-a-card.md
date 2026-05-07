---
title: "Day 2 — I Made a Card"
date: 2026-05-06
tag: Figma
summary: "The most basic one. Probably for the first time in a long time with this much attention to every element."
---

I made a card today.

The most basic one. Probably for the first time in a long time with this much attention to every single element — the padding, the stroke colour, the shadow opacity, the corner radius. Things I'd usually just eyeball and move on from.

Here's what I built: an image placeholder at the top, then tag, title, date, and summary below it. Auto-layout on the text group first, then auto-layout on the whole card frame.

The thing that clicked: once I applied auto-layout to the card frame with all the elements inside it, I realised the original blank rectangle I started with wasn't needed anymore. The frame *with* the elements *is* the card. Add a background colour to that frame and you're done. I'd been treating the container and the content as two separate things. They're not.

The card now grows vertically as the title gets longer. One component, two instances, different titles — both look right without me touching anything.

I also wanted the tag — "WATER" — to stay on one line no matter what. Turns out it was an easy fix. Set the text layer to Fixed size, then scroll all the way down in the text options — there's a Truncate setting sitting quietly at the bottom. Turn it on and any text that's too long just shows "..." instead of wrapping. Simple once you know where to look.

---

**What I learned**

The frame with elements inside it is the card. Not a separate container.
Fixed size + Truncate = one line, always.

*— Littlethings*
