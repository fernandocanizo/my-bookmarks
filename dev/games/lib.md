# Libraries

- [Phaser](https://phaser.io/)
  Untested. Got a publication with news from the library development and tutorials.

- [KaPlay](https://kaplayjs.com/)
  2024-11-03 link from DevCafe.
  > KAPLAY is a JavaScript and TypeScript game library that makes it easy to
  > create games for the web. It's free, open-source and fun. KAPLAY makes game
  > development FFF (Fun, Fast, Fantastic).

  The repo has some example assets that you can use to start a simple game:
  [assets](https://github.com/kaplayjs/kaplay/tree/master/examples)

  But also there's another repo that has more or less the same assets:
  `pnpm i ` [@kaplayjs/crew](https://github.com/kaplayjs/crew/)

## Maps

- [json-map-format](https://doc.mapeditor.org/en/stable/reference/json-map-format/)
  A standar map format that (I think) some tool named _Tiled_ produces.

  Kaboomjs could import these maps using a plugin:
  [tiled-kaboom](https://github.com/notnullgames/tiled-kaboom/blob/main/tiled-kaboom.js)

  @dragoncoder047 said (2026-02-12) that it may be easy to port it to Kaplayjs, so there's an idea for collaboration.

  Anyway, map-wise, I don't need any of these things, as Kaplayjs already provides a way to create maps. Maybe the benefit of using that _Tiled_ thingy would be that you create the map with visual tools, instead of editing a text file and reloading the page.

