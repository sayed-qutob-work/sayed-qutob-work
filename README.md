### Hi, I'm Sayed 👋

I build **local-first tools** that run entirely on your own machine: offline text-to-speech, accessibility helpers, and Linux desktop tweaks. Mostly Python, on Linux (Hyprland / Omarchy) and Windows.

#### 🔊 [Kokoro Read-Aloud](https://github.com/sayed-qutob-work/kokoro-read-aloud)

Select text in any app, press <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>R</kbd>, and a neural voice running on your own machine reads it aloud. No GPU needed: on an i5-12400F it starts speaking about 30 ms after it gets the text and synthesizes 50–70× faster than it plays. Linux (Omarchy, Fedora GNOME) and Windows 11, and your text never leaves the machine.

<a href="https://github.com/sayed-qutob-work/kokoro-read-aloud"><img src="https://github.com/sayed-qutob-work/kokoro-read-aloud/raw/main/docs/img/demo.gif" width="600" alt="Two sentences of a Wikipedia article are selected. After Ctrl+Alt+R, a caption strip appears and underlines each sentence as it is read aloud."></a>

#### More projects

| Project | What it does |
|---|---|
| [**LifeGraph**](https://github.com/sayed-qutob-work/LifeGraph) | A local personal knowledge graph: plain-English facts become a typed graph you can query and paste into any AI chat as context. Ollama, SQLite, Flask, MCP server, 550+ tests. Paused after a measured experiment; the [write-up](https://github.com/sayed-qutob-work/LifeGraph#the-experiment-passive-capture) has the numbers. |
| [**WinSnap**](https://github.com/sayed-qutob-work/winsnap) | Moves your Windows setup to a new PC: theme, wallpaper, fonts, taskbar pins, apps via winget, mouse and keyboard settings, and more. CLI and PyQt6 app, with dry-run and verify-after-restore. |

**Open source:** added word timestamps to [Paradee](https://github.com/sahilmahendrakar/paradee), an 8 MB text-to-speech model, so apps know when each word is spoken ([#8](https://github.com/sahilmahendrakar/paradee/pull/8), merged).

**Tools:** Python · PyQt6 · QML · Flask · SQLite · Ollama · JavaScript · Bash · pytest + Hypothesis

📫 [sayed.qutob.work@gmail.com](mailto:sayed.qutob.work@gmail.com) · [LinkedIn](https://www.linkedin.com/in/sayed-qutob/)
