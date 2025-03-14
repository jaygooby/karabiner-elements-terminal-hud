# About

A fullscreen terminal toggle (like iTerm2 or Guake; RIP [Visor](https://visor.binaryage.com) & [TotalTerminal](https://totalterminal.binaryage.com)) using the built-in macOS `Terminal.app`.

Uses [Karabiner-Elements](https://github.com/pqrs-org/Karabiner-Elements) because I already use it.

# How to install

Choose [`Complex Modifications` in Karabiner Elements, then click the `Add your own rule` button](https://karabiner-elements.pqrs.org/docs/manual/configuration/add-your-own-complex-modifications/). Copy and paste this repo's [`show.json`](./show.json) then do it again for [`hide.json`](./hide.json).

Now when you press `Control`+`Space` on your keyboard, the terminal should toggle.

# Why
I got fed up with iTerm2 eating energy and don't use any of its advanced features other than the fullscreen toggle, so I thought I'd try it with the macOS native Terminal.app.

# Does it work?
It's OK! You still get Terminal showing up in the cmd-tab list of apps, which isn't a deal breaker for me, although it's a bit meh, because you can tab to it and it won't be fullscreen, but a quick `Control`+`Space` and you're fullscreen again.

Sometimes when you toggle, the `f` keypress seems detatched from its modifers, so Terminal shows you a search bar at the top. Slightly annoying :(

# Old stuff
The [`old-experiments`](./old-experiments) directory in the repo has various examples of me trying to launch using the shell, and then showing and hiding the terminal with Applescript until I worked out how to do it all with pure Karabiner-Elements commands. 

If you want to mess around with the `osascript` calls you'll need to enable various permissions in macOS's System Settings, Privacy & Security - which you should get as OS pop-up warnings.