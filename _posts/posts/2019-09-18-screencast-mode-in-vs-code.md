---
layout: post
title: Screencast Mode in VS Code
category: posts
updated: 2021-12-09
---

This week I released an update to my VS Code extension that lets you [open a flexbox cheatsheet](https://marketplace.visualstudio.com/items?itemName=dzhavat.css-flexbox-cheatsheet) directly in the editor. The update contains a couple of things but a tiny detail that I really like in particular is a small icon shown in front of the `flex` keyword to make it easily recognizable. But because of it, I had to make new demo gifs because the old ones didn’t have the icon in them.

For recording gifs I use [ScreenToGif](https://www.screentogif.com/). It’s an excellent little program but something I miss in it is the option to show the keys being pressed during a recording. I needed this because one way to open the cheatsheet is by searching for a specific command in the “Command Pallete”. So I wanted the key combination to be visible in the gif.

VS Code, once again, helped me out because it has this exact functionality already build-in! It’s called “Screencast Mode”. You can toggle it on and off by searching for it in the “Command Pallete”. Here’s how:

- Press `Ctrl+Shift+P` (Win, Linux) or `Cmd+Shift+P` (Mac) and search for `Toggle Screencast Mode`.
- Press `Enter` to activate it.
- (Repeat the steps to deactivate it)

Now every keystroke will be shown in an overlay. Check this out:

<figure>
  <img src="/assets/img/2019/09/18/hey.gif" alt="">
  <figcaption>Pressed keys appear in an overlay when “Screencast Mode” is activated</figcaption>
</figure>

But wait, there’s more!

By default, activating this mode will show all keystrokes in the overlay. Oftentimes this might not be what you want. Wouldn’t it be nice if the overlay only showed the keyboard shortcuts (key combinations) and nothing more?

Well, VS Code has got you covered! Again! 😎

If you open the settings (`Ctrl+,` (Win, Linux), `Cmd+,` (Mac)) and search for `Screencast Mode`, you’ll find all related settings. One of them is `Only show keyboard shortcuts in screencast Mode`.

**Update**: The screenshot shows all settings related to “Screencast Mode” as of VS Code v1.63.0.

<figure>
  <img src="/assets/img/2019/09/18/screencast-mode-settings.jpg" alt="">
  <figcaption>“Screencast Mode” Settings</figcaption>
</figure>

The other settings will help you customize the mouse indicator, the overlay timeout, the font size of the overlay text, etc.

Now you know how to show all those smart key shortcuts in your videos/gifs. 🚀
