# Pi

A minimal terminal coding harness.

Can explain its own features and loop up its docs.

- [Pi repo](https://github.com/earendil-works/pi)
- [Pi site](https://shittycodingagent.ai/)
- [Pi site (mirror)](https://pi.dev/)
  Has the exact same content as shittycodingagent.ai, I don't know why don't they redirect.

- [Extensions, skills, etc. Pi-related](https://pi.dev/packages)

## Extensions I'm currently using

Try to use the GitHub installation always, unless it's a mono-repo with more
extensions I don't care about. It's easier to compose and easier to find the
repo later to search for documentation or whatever.

- [pi-web-access](https://github.com/nicobailon/pi-web-access)
  ```
  pi install git:github.com/nicobailon/pi-web-access
  ```
- [pi-tool-display](https://github.com/MasuRii/pi-tool-display)
  Compacts Pi output.
  ```
  pi install git:github.com/MasuRii/pi-tool-display
  ```

- [pi-subagents](https://github.com/nicobailon/pi-subagents)
  ```
  pi install git:github.com/nicobailon/pi-subagents
  ```

- [friday](https://github.com/dantetekanem/friday)
  Adds a dedicated communications side panel. All conversation is routed to a separate tmux pane with typewriter effect, keeping your main window clean for code, diffs, and command output.

  ```
  pi install git:github.com/dantetekanem/friday
  ```

- [pi-token-burden](https://github.com/Whamp/pi-token-burden)
  Visualize consumed context by default stuff.
  ```
  pi install git:github.com/Whamp/pi-token-burden
  ```

- [dreki pi-extensions](https://github.com/dreki-gg/pi-extensions)
  A monorepo with several extensions, I only added `@dreki-gg/pi-context7` and
  `@dreki-gg/pi-lsp`.
  ```
  pi install npm:@dreki-gg/pi-context7
  pi install npm:@dreki-gg/pi-lsp
  ```

- [pi-hermes-memory](https://github.com/chandra447/pi-hermes-memory)
  Hermes-style persistent memory and learning loop for Pi coding agent.
  ```sh
  # Install
  pi install git:github.com/chandra447/pi-hermes-memory 

  # Index your past sessions (one-time)
  /memory-index-sessions

  # Backfill older Markdown memories into SQLite search (optional)
  /memory-sync-markdown

  # Learn how to use it
  /learn-memory-tool
  ```

- [pi-smart-btw](https://github.com/IgorWarzocha/howaboua-pi-stuff)
  This is a mono-repo with several tools, but I'm only interested on `pi-smart-btw`
  ```
  pi install npm:@howaboua/pi-smart-btw
  ```

- [pi-mcp-adapter](https://github.com/nicobailon/pi-mcp-adapter)
  Token-efficient MCP adapter for Pi coding agent.
  ```
  pi install npm:pi-mcp-adapter
  ```

## Extensions that I really should try

- [pi-llm-wiki](https://github.com/Kausik-A/pi-llm-wiki)
  Claims that my system works, but it's inefficient. I'd like to try this thing
  later, but after doing a deep analysis, talking with mmm, so I'm adding the
  link for future reference, but won't install it right now.

  **2026-06-17:** I want to really try this and start building a knowledge base
  for all the things that interest me. But right now I'm installing the
  extensions I use to use in Borrow machine, into Cygnus so I have the same
  setup. **LOOK INTO THIS LATER**

- [pi-archimedes](https://github.com/danielcherubini/pi-archimedes)
 **2026-06-17:**  
  Another mono-repo with several extensions that work cohesively. I'm interested in the good diff with colors. But I think it would pay to run a version of pi with just this set of extensions. I think pi parameters allow for that, so I could have a test run without my other installed extensions getting in the way. Try that idea.

- [pi-zentui](https://github.com/lmilojevicc/pi-zentui)
 **2026-06-17:**  
  I'm interested in having an OpenCode-like question tabs, check if this provides that TUI interaction.

## Other extensions that look interesting

- [pi-phone](https://github.com/MaliNamNam/pi-phone)
  Looks just like what I need for mmm, but right now I don't have time to make
  a Tailscale account and connect all the stuff. So, try it later.

- [rpiv-mono](https://github.com/juicesharp/rpiv-mono)
  A mono-repo with 12 extensions, I use to use `rpiv-ask-user-question` and `rpiv-todo`.

  **2026-06-17:** But I don't feel like installing them again, let's see if I need them down the road.

- [pi-btw](https://github.com/dbachelder/pi-btw)
  **2026-06-17:** I use to use this `/btw`, but found `pi-smart-btw` which looks more potent, so I'll try that one and see. Keep this one for reference just in case the other one blows.

- [Nico Bailon](https://github.com/nicobailon)
  A guy very into creating lots of plugins for Pi, I'm currently only using `pi-mcp-adapter` and `pi-subagents`, but worth checking more of his stuff.

- [oh-my-pi](https://github.com/can1357/oh-my-pi)
  Looks pretty awesome, but I don't think I use it right now, as my main
  interest currently is using Pi as my personal assistant, so I don't use it much
  to develop, except for internal commands.

  But keep an eye on this project, has some pretty cool features.

- [pi-dots](https://github.com/VenTheZone/pi-dots)
  Claims to be "all the skills you will ever need". It's software development
  oriented, mostly, and I'm not using Pi that way, so I don't want to contaminate
  it. But the repository is pretty cool, so let's save it.

- [pi-agent-dashboard](https://github.com/BlackBeltTechnology/pi-agent-dashboard)
  Real-time web dashboard for pi coding-agent sessions. Multi-session view,
  live chat mirroring, integrated terminal, diff viewer, pi-flows execution,
  and mobile-first remote control via mDNS or zrok tunnel. Coexists with pi's
  TUI, doesn't replace it.

  Works in the browser and can controll an army of Pi agents doing stuff.

  I currently don't have an use case for this, but keep it at hand.

## Extensions dropped and why

- [pi-pane](https://github.com/visua1hue/pi-pane)
  Adds a nicer input box TUI.
  ```
  pi install git:github.com/visua1hue/pi-pane
  ```
  **2026-06-17:** removed, it conflicts with `pi-tool-display` and that one
  already provides what pi-pane provides plus many other things, including a
  good diffing tool. When both are installed Pi crashes, cause they both modify
  TUI size, but they don't account for each other.

- [pi-telegram-plus](https://github.com/jalyfeng/pi-telegram-plus)
  It stablishes a two way connection with a running Pi session, meaning if you are in your laptop, chatting in that session, you'll receive all the in-between message from Pi thinking and all that shit.

  I wanted to be able to send a message from Telegram, reach the running session of Pi, and run a command or a prompt. I don't want my notebook session to send shit to Telegram.

- [telepi](https://github.com/benedict2310/TelePi)
  This one gave a bunch of npm deprecations, looks like it used ancient package, probably unmaintained. And then I followed the instructions to connect it and nothing happened. So ditched.

