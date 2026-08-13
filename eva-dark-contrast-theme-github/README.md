# Eva Dark Contrast

A custom dark VS Code theme, based on Eva Dark with darker chrome (tabs bar, terminal) and a purple accent.

## Install

Search for **Eva Dark Contrast** in the VS Code Extensions panel, or install from the [Marketplace](https://marketplace.visualstudio.com/items?itemName=DaniyalAkbar.eva-dark-contrast-theme):

```bash
code --install-extension DaniyalAkbar.eva-dark-contrast-theme
```

## Install (from source)

1. Copy this folder into `~/.vscode/extensions/eva-dark-contrast-theme`
2. Reload VS Code
3. `Cmd+Shift+P` → "Preferences: Color Theme" → select **Eva Dark Contrast**

## Package as `.vsix`

```bash
npm install -g @vscode/vsce
cd eva-dark-contrast-theme
vsce package
```

This produces `eva-dark-contrast-theme-1.0.0.vsix`, installable via:

```bash
code --install-extension eva-dark-contrast-theme-1.0.0.vsix
```
