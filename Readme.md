# VS Code Configuration

This repository contains my personalized VS Code configuration, including keybindings, settings, installed extensions, and theme preferences.

## 📁 File Structure
```
VsCode-Config/
├─ .vscode/
│  ├─ extensions.txt
│  └─ theme.txt
├─ keyBinding/
│  ├─ keyBinding1.json
│  └─ keyBinding2.json
├─ Readme.md
└─ setting.json

```

---

## ⚙️ Settings

My custom VS Code settings are stored in `settings.json`. These settings include:
- Editor and terminal customization
- Font and theme preferences
- Auto-formatting and linting rules
- Performance optimizations
- Custom workspace configurations

### Example (`.vscode/settings.json`):
```json
{
  "editor.fontFamily": "Hack Nerd Font Mono, Courier New",
  "editor.fontSize": 14,
  "workbench.colorTheme": "One Dark Pro",
  "editor.formatOnSave": true,
  "terminal.integrated.fontFamily": "Hack Nerd Font Mono",
  "editor.cursorBlinking": "smooth",
  "editor.rulers": [80, 100],
  "window.zoomLevel": 1
}
```

---

## ⌨️ Keybindings

Custom keybindings are stored in `keybindings.json`. Some notable shortcuts:
- `Ctrl + N` → Navigate to next quick open item
- `Ctrl + P` → Navigate to previous quick open item
- `J` / `K` → Move focus up/down in the sidebar (Vim mode)
- `A` → Create a new file in the explorer
- `F` → Create a new folder in the explorer
- `C/X/P/D/R` → Copy, Cut, Paste, Delete, Rename files
- `Ctrl + H/J/K/L` → Navigate editors using Harpoon
- `Ctrl + S` → Toggle Sidebar
- `Ctrl + Shift + T` → Create a new TypeScript file using Quokka
- `Alt + Shift + Up/Down` → Duplicate selected lines
- `Ctrl + Shift + [ / ]` → Fold/Unfold all code blocks

---

## 🔌 Installed Extensions

A list of all installed extensions is saved in `extensions.txt`. To install them, run:
```sh
cat .vscode/extensions.txt | xargs -n 1 code --install-extension
```

### Example (`.vscode/extensions.txt`):
```
aaron-bond.better-comments
bradlc.vscode-tailwindcss
dbaeumer.vscode-eslint
dsznajder.es7-react-js-snippets
esbenp.prettier-vscode
formulahendry.auto-close-tag
formulahendry.auto-rename-t
```

---

## 🎨 Theme

The current theme is saved in `theme.txt`. My preferred themes include:
- `One Dark Pro`
- `Dracula Official`
- `Tokyo Night`
- `Night Owl`
- `SynthWave '84`
- `Gruvbox Concoctis`

### Example (`.vscode/theme.txt`):
```
One Dark Pro
```

---

## 🚀 Usage
1. Copy the `.vscode/` folder to your VS Code settings directory.
2. Install extensions using `extensions.txt`.
3. Add custom snippets for frequently used code patterns.
4. Enjoy your customized VS Code setup!

---
<!-- 
## 🛠️ Additional Customization
- **Snippets:** Store frequently used code patterns in `.vscode/snippets/`.
- **Workspace Settings:** Override settings per project using `.vscode/settings.json` in project directories.
- **Icons:** Customize file and folder icons using the `vscode-icons` extension. -->



## 📌 Notes
- This setup is optimized for efficiency and developer experience.
- Modify `settings.json` and `keybindings.json` to match your preferences.
- Keep your `extensions.txt` updated for easy replication.

Happy Coding! 🚀
