# Oceanic Wind Theme

A Visual Studio Code theme based on color combinations from [Oceanic Next](https://github.com/voronianski/oceanic-next-color-scheme) replaced and customized with [Tailwind CSS color palette](https://tailwindcss.com/docs/customizing-colors).

Almost every color you find is using a Tailwind color, except some rare cases I couldn´t test and may appear default VSCode color.

I did my best for providing good contrast in almost all combinations posible fullfilling AA contrast ratio requirements.

## Installation
## Preview

## Recommended settings
I like the default font family `Consolas` used in Windows with a font size of 16. Another combination I also like is `Cascadia Code` with ligatures. Font family is a personal decision, use whatever you are used to:
````
{
	"editor.bracketPairColorization.enabled": true,
	"editor.fontLigatures": true,
  "editor.fontFamily": "Cascadia Code, Consolas, 'Courier New', monospace",
  "editor.lineHeight": 1.5,
  "editor.fontSize": 15,
  "editor.fontWeight": "normal"
}
````

## Customize
You can overwrite colors for a given theme in VSCode settings. I have created different set of colors to provide accent color to VSCode, if you would like to try another color instead of blue for the accent of your IDE, you can use these differente combinations:
- Indigo
- Green
- Rose
- Teal
- Fuchsia
- Amber
- Esmerald

If you want to use an accent color, but the selection color is too colourful, you can use a neutral color:
````
{
	"editor.selectionBackground": "#334155"
}
````
Sidebar, tabs and editor have the same background, if you would like to try with darker color for sidebar and tabs you can try this combinations:

## Misc
I have tested this theme focused in my day to day workflow, with HTML, CSS, Javascript, Typescript and developing with frameworks such as Angular, Vue and React. Further more, I have tried with files you cand find in demo folder (thanks to Wes Bos and Sarah Drasner).

If you find something amiss, you have any suggestion or improvement, please feel free to open and issue. I'm sure there are things I missed.

I am not a designer, so any help or feedback would be really apreciated.
## Thanks to
- [Sarah Drasner](https://twitter.com/sarah_edo), I picked up some ideas from her [blog post about creating themes](https://css-tricks.com/creating-a-vs-code-theme/). I also copied files from her demo folder on [Night Owl theme](https://github.com/sdras/night-owl-vscode-theme).
- [Wes Bos](https://twitter.com/wesbos), I grabbed some demo examples from his [Cobalt2 theme](https://github.com/wesbos/cobalt2-vscode).
- [Tailwind CSS team](https://twitter.com/tailwindcss), I used their beautiful color palette in order to choose every color in this theme.

"activityBarBadge.foreground": "#ECFDF5", // 50
"list.focusHighlightForeground": "#6EE7B7", // 300
"textLink.foreground": "#34D399", // 400
"notificationLink.foreground": "#34D399", // 400
"textLink.activeForeground": "#34D399", // 400
"list.highlightForeground": "#34D399", // 400
"editorLineNumber.activeForeground": "#34D399", // 400
"editorLink.activeForeground": "#34D399", // 400
"welcomePage.progress.foreground": "#34D399", // 400
"toolbar.hoverBackground": "#10B98180", // 500
"tab.activeModifiedBorder": "#10B981", // 500
"tab.inactiveModifiedBorder": "#10B981", // 500
"editor.selectionBackground": "#10B98166", // 500
"editor.inactiveSelectionBackground": "#10B9814d", // 500
"editor.selectionHighlightBackground": "#10B9814d", // 500
"editorOverviewRuler.selectionHighlightForeground": "#10B9814d", // 500
"peekViewResult.selectionBackground": "#10B98166", // 500
"extensionButton.prominentHoverBackground": "#10B981", // 500
"editor.snippetFinalTabstopHighlightBorder": "#10B981", // 500
"button.hoverBackground": "#059669", // 600
"focusBorder": "#059669", // 600
"sash.hoverBorder": "#059669", // 600
"textBlockQuote.border": "#059669", // 600
"button.background": "#059669", // 600
"checkbox.background":"#059669", // 600
"inputOption.activeBackground": "#059669", // 600
"inputOption.activeBorder": "#05966900", // 600
"progressBar.background": "#059669", // 600
"activityBar.dropBorder": "#059669", // 600
"activityBarBadge.background": "#059669", // 600
"statusBar.background": "#059669", // 600
"statusBarItem.remoteBackground": "#059669", // 600
"extensionButton.prominentBackground": "#059669", // 600
"extensionBadge.remoteBackground": "#059669", // 600
"settings.modifiedItemIndicator": "#059669", // 600
"settings.checkboxBackground": "#059669", // 600
"notebook.cellInsertionIndicator": "#059669", // 600
"notebook.focusedCellBorder": "#059669", // 600
"notebook.focusedEditorBorder": "#059669", // 600
"ports.iconRunningProcessForeground": "#059669", // 600
"editor.hoverHighlightBackground": "#04785775", // 700
"editor.foldBackground": "#0478574d", // 700
"quickInputList.focusBackground": "#065F46", // 800
"list.focusOutline": "#065F46", // 800
"editorSuggestWidget.selectedBackground": "#065F46", // 800
"menu.selectionBackground": "#065F46", // 800
"banner.background": "#065F46", // 800
"notebook.cellBorderColor": "#065F46", // 800
"notebook.inactiveFocusedCellBorder": "#065F46", // 800
"notebook.selectedCellBackground": "#065F46", // 800
"notebook.selectedCellBorder": "#065F46", // 800
"list.activeSelectionBackground": "#064E3B", // 900
"list.inactiveSelectionBackground": "#064E3B", // 900
"list.dropBackground": "#064E3B", // 900
"peekViewEditor.background": "#064E3B66", // 900
"peekViewEditorGutter.background": "#064E3B66", // 900
