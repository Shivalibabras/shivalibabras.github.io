---
title: "Step 0"
date: 2026-05-05
tag: Figma
summary: "I built a button today. It took longer than it should have.."
---

Auto-layouts scare me. One wrong click and everything shifts — and I'd rather start from scratch than figure out what went wrong. Like a password with one wrong character. Easier to retype the whole thing than find the mistake.

I've been doing that for years. And I need to stop.

So today I gave myself grace. I went back to basics. I built a button.

Not a fancy one. Just a button. With auto-layout, which I had to redo multiple times because I kept selecting the wrong thing before hitting Shift+A. Turns out — you have to select both layers first. The rectangle and the text. Together. Then Shift+A wraps them and suddenly it behaves like a real button instead of two things awkwardly sharing a frame.

Then I made it a component. Then I added variants: Primary, Secondary, Destructive. States: Default, Hover, Disabled. A Boolean property to toggle the icon on and off.

The Boolean property part was confusing. I created the property on the component but couldn't figure out where to link the icon to it. Turns out it's not in the main panel, you have to select the icon layer, scroll down to the Appearance section, and link it from there.

Then I tried to prototype it. It worked, but I realised I'd only connected the states on one screen. Move to a new screen and nothing. Back to zero.

So I learned the difference between that and interactive components, where the behaviour lives inside the component itself. Baked in. Drag it anywhere in any file and it already knows how to animate on hover. Already knows what Pressed looks like. You never wire the same thing twice.

That moment when I dropped the component onto a new frame and it just worked and that's the thing I'll remember from today.

---

**What I learned**

Built-in behaviour of components

I'm publishing this not because it's finished. But because future me will forget and she deserves to look back without being tensed.

*- Littlethings*
