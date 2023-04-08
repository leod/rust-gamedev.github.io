+++
title = "This Month in Rust GameDev #44 - March 2023"
transparent = true
date = 2023-04-05
draft = true
+++

<!-- no toc -->

<!-- Check the post with markdownlint-->

Welcome to the 44th issue of the Rust GameDev Workgroup's
monthly newsletter.
[Rust] is a systems language pursuing the trifecta:
safety, concurrency, and speed.
These goals are well-aligned with game development.
We hope to build an inviting ecosystem for anyone wishing
to use Rust in their development process!
Want to get involved? [Join the Rust GameDev working group!][join]

You can follow the newsletter creation process
by watching [the coordination issues][coordination].
Want something mentioned in the next newsletter?
[Send us a pull request][pr].
Feel free to send PRs about your own projects!

[Rust]: https://rust-lang.org
[join]: https://github.com/rust-gamedev/wg#join-the-fun
[pr]: https://github.com/rust-gamedev/rust-gamedev.github.io
[coordination]: https://github.com/rust-gamedev/rust-gamedev.github.io/issues?q=label%3Acoordination

- [Announcements](#announcements)
- [Game Updates](#game-updates)
- [Engine Updates](#engine-updates)
- [Learning Material Updates](#learning-material-updates)
- [Tooling Updates](#tooling-updates)
- [Library Updates](#library-updates)
- [Other News](#other-news)
- [Popular Workgroup Issues in Github](#popular-workgroup-issues-in-github)
- [Discussions](#discussions)
- [Requests for Contribution](#requests-for-contribution)
- [Jobs](#jobs)
- [Bonus](#bonus)

<!--
Ideal section structure is:

```
### [Title]

![image/GIF description](image link)
_image caption_

A paragraph or two with a summary and [useful links].

_Discussions:
[/r/rust](https://reddit.com/r/rust/todo),
[twitter](https://twitter.com/todo/status/123456)_

[Title]: https://first.link
[useful links]: https://other.link
```

If needed, a section can be split into subsections with a "------" delimiter.
-->

## Announcements

## Game Updates

### [8bit Duels]

![movement_animations](8bit-duels-game.png)
_An 8bit Duels match_

[@ThousandthStar] is creating a simple multiplayer turn-based strategy using the
[Bevy Engine]. The [latest devlog] brings features like ownership indicators,
movement and attack animations, and a chat system.

The game is under development. The [8-bit Discord] is the best place to talk
about the game.

8bit Duels will be getting UI updates next, and the first version should release
soon after that. Other troops are coming as well.

_Discussions: [8-bit Discord]_

[8bit Duels]: https://thousandthstar.github.io/
[@ThousandthStar]: https://github.com/ThousandthStar
[Bevy Engine]: https://bevyengine.org/
[latest devlog]: https://thousandthstar.github.io/posts/8bd/8bd-part6/
[8-bit Discord]: https://discord.com/invite/NbBcF4bGU5

## Engine Updates

## Learning Material Updates

### Developing an editor with egui

![Gif displaying the functionality of the editor](TheGrimsey-Editor.gif)

[@TheGrimsey] published a three-part series of articles about developing a Spell
Editor with egui.

- ["Databases & Editors (1/3)"] covers displaying egui windows & tables of
  entries.
- ["Editors (2/3): Editing entries"] elaborates on handling editing of entries &
  properties such as enums.
- Finally, ["Editors (3/3): Selection dialog & new entries"] talks about
  developing a selection dialog and creating new entries.

[@TheGrimsey]: https://mastodon.social/@TheGrimsey
["Databases & Editors (1/3)"]: https://thegrimsey.net/2023/03/07/Bevy-Four-Editor.html
["Editors (2/3): Editing entries"]: https://thegrimsey.net/2023/03/12/Bevy-Five-Editor-Two.html
["Editors (3/3): Selection dialog & new entries"]: https://thegrimsey.net/2023/03/21/Bevy-Six-Editor-Three.html

## Tooling Updates

## Library Updates

### [`bevy_text_mode`]

![Screenshot of 1-bit sprites drawn using bevy_text_mode.](bevy_text_mode.png)

[`bevy_text_mode`] ([GitHub][bevy_text_mode-src]) by [yopox] is a Bevy plugin which
makes it possible to set the background and the foreground color of a texture atlas
sprite (built-in Bevy sprites only have a tint property).
This plugin is convenient when using 1-bit tilesets such as [MRMOTEXT].

The 0.1 release adds a `TextModeTextureAtlasSprite` component with
configurable background, foreground, x/y flip and opacity.

_Discussion: [Mastodon](https://mstdn.social/@yopox/110010264001721310)_

[`bevy_text_mode`]: https://crates.io/crates/bevy_text_mode
[bevy_text_mode-src]: https://github.com/yopox/bevy_text_mode
[yopox]: https://github.com/yopox
[MRMOTEXT]: https://mrmotarius.itch.io/mrmotext

## Popular Workgroup Issues in Github

<!-- Up to 10 links to interesting issues -->

## Other News

<!-- One-liners for plan items that haven't got their own sections. -->

## Discussions

<!-- Links to handpicked reddit/twitter/urlo/etc threads that provide
useful information -->

## Requests for Contribution

<!-- Links to "good first issue"-labels or direct links to specific tasks -->

## Jobs

<!-- An optional section for new jobs related to Rust gamedev -->

## Bonus

<!-- Bonus section to make the newsletter more interesting
and highlight events from the past. -->

------

That's all news for today, thanks for reading!

Want something mentioned in the next newsletter?
[Send us a pull request][pr].

Also, subscribe to [@rust_gamedev on Twitter][@rust_gamedev]
or [/r/rust_gamedev subreddit][/r/rust_gamedev] if you want to receive fresh news!

<!--
TODO: Add real links and un-comment once this post is published
**Discuss this post on**:
[/r/rust_gamedev](TODO),
[Twitter](TODO),
[Discord](https://discord.gg/yNtPTb2).
-->

[/r/rust_gamedev]: https://reddit.com/r/rust_gamedev
[@rust_gamedev]: https://twitter.com/rust_gamedev