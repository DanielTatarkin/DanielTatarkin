### Hi there, I'm Daniel 👋

- I'm a Software Engineer at Gemini

### 📫 Contact Me:
* [LinkedIn](https://linkedin.com/in/danieltatarkin)

#### macOS Dock Tweaks

Run this command in Terminal to remove delays and show hidden apps as faded:
```bash
defaults write com.apple.dock autohide-delay -float 0; defaults write com.apple.dock autohide-time-modifier -float 0; defaults write com.apple.dock showhidden -bool TRUE; killall Dock
```

Restore Defaults:
```bash
defaults delete com.apple.dock autohide-delay; defaults delete com.apple.dock autohide-time-modifier; defaults delete com.apple.dock showhidden; killall Dock
```


<!--
**DanielTatarkin/DanielTatarkin** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
