# Backplane Theme

## Development Testing

To test theme changes in development mode:

1. Open this folder in VS Code
2. Click the "Run and Debug" icon in the sidebar (or press `Cmd+Shift+D`)
3. Click the green "Run" button (or press `F5`)
4. This will open a new VS Code window with the theme loaded
5. Edit `themes/backplane.json` and save to see live changes (hot reload)

## Installation

### Option 1: Install Locally

1. Clone this repository
2. Open the folder in VS Code
3. Run `npm install` to install dependencies
4. Run `npm run package` to create the VSIX package
5. Run `surf --uninstall-extension me.backplane` to remove the existing theme
6. Run `surf --install-extension backplane-0.0.1.vsix` to install the new version
7. Press `Cmd+K Cmd+T` and select "Backplane"

### Option 2: Install from VS Code Marketplace (Coming Soon)

This theme is not yet published to the VS Code Marketplace. When it is published, you will be able to install it by:

1. Opening VS Code
2. Pressing `Cmd+Shift+X` to open Extensions
3. Searching for "Backplane"
4. Clicking "Install"
5. Pressing `Cmd+K Cmd+T` and selecting "Backplane"

---

- To package or publish this theme, see [VS Code Theme documentation](https://code.visualstudio.com/api/extension-guides/color-theme).
