# Generate accent color

You can generate your own accent color, modifying the settings below. Keep in mind, you should have 10 shades of the color you want to apply. I used [Tailwind colors](https://tailwindcss.com/docs/customizing-colors), which go from 50 to 900, being 50 the lightest shade and 900 the darkest one.

Consider that for [colors with a length greater than 6](https://code.visualstudio.com/api/references/theme-color#color-formats), the last two characters set the transparency in hexadecimal notation. For example:

> "#10b981**1a**", // 500
- Shade 500, color `#10b981`.
- Opacity 10% (equivalent to opacity 0.1 in traditional CSS).

You can replace **emerald** colors with your own colors below. Thereafter you should check if you like the result, if color has enough contrast in the interface, etc.

Shade | Hex      
---   | ---      
50    | `#ecfdf5`
100   | `#d1fae5`
200   | `#a7f3d0`
300   | `#6ee7b7`
400   | `#34d399`
500   | `#10b981`
600   | `#059669`
700   | `#047857`
800   | `#065f46`
900   | `#064e3b`

```
"workbench.colorCustomizations": {
  "[Oceanic Wind]": {
    "activityBarBadge.foreground": "#ecfdf5", // 50
    "list.focusHighlightForeground": "#6ee7b7", // 300
    "textLink.foreground": "#34d399", // 400
    "notificationLink.foreground": "#34d399", // 400
    "textLink.activeForeground": "#34d399", // 400
    "pickerGroup.foreground": "#34d399", // 400
    "list.highlightForeground": "#34d399", // 400
    "editorLineNumber.activeForeground": "#34d399", // 400
    "editorLink.activeForeground": "#34d399", // 400
    "welcomePage.progress.foreground": "#34d399", // 400
    "toolbar.hoverBackground": "#10b98180", // 500
    "tab.activeModifiedBorder": "#10b981", // 500
    "tab.inactiveModifiedBorder": "#10b981", // 500
    "editor.selectionBackground": "#10b98133", // 500
    "editor.inactiveSelectionBackground": "#10b9811a", // 500
    "editor.selectionHighlightBackground": "#10b9811a", // 500
    "editorOverviewRuler.selectionHighlightForeground": "#10b9811a", // 500
    "peekViewResult.selectionBackground": "#10b98133", // 500
    "extensionButton.prominentHoverBackground": "#059669", // 600
    "editor.snippetFinalTabstopHighlightBorder": "#10b981", // 500
    "button.hoverBackground": "#059669", // 600
    "focusBorder": "#059669", // 600
    "sash.hoverBorder": "#059669", // 600
    "textBlockQuote.border": "#059669", // 600
    "checkbox.background": "#059669", // 600
    "inputOption.activeBackground": "#059669", // 600
    "inputOption.activeBorder": "#05966900", // 600
    "progressBar.background": "#059669", // 600
    "activityBar.dropBorder": "#059669", // 600
    "activityBarBadge.background": "#059669", // 600
    "statusBar.background": "#059669", // 600
    "statusBarItem.remoteBackground": "#059669", // 600
    "extensionBadge.remoteBackground": "#059669", // 600
    "settings.modifiedItemIndicator": "#059669", // 600
    "settings.checkboxBackground": "#059669", // 600
    "notebook.cellInsertionIndicator": "#059669", // 600
    "notebook.focusedCellBorder": "#059669", // 600
    "notebook.focusedEditorBorder": "#059669", // 600
    "ports.iconRunningProcessForeground": "#059669", // 600
    "button.background": "#047857", // 700
    "extensionButton.prominentBackground": "#047857", // 700
    "editor.hoverHighlightBackground": "#04785775", // 700
    "editor.foldBackground": "#0478574d", // 700
    "quickInputList.focusBackground": "#065f46", // 800
    "list.focusOutline": "#065f46", // 800
    "editorSuggestWidget.selectedBackground": "#065f46", // 800
    "menu.selectionBackground": "#065f46", // 800
    "banner.background": "#065f46", // 800
    "notebook.cellBorderColor": "#065f46", // 800
    "notebook.inactiveFocusedCellBorder": "#065f46", // 800
    "notebook.selectedCellBackground": "#065f46", // 800
    "notebook.selectedCellBorder": "#065f46", // 800
    "list.activeSelectionBackground": "#064e3b", // 900
    "list.inactiveSelectionBackground": "#064e3b", // 900
    "list.dropBackground": "#064e3b", // 900
    "peekViewEditor.background": "#064e3b66", // 900
    "peekViewEditorGutter.background": "#064e3b66" // 900
  }
}
```