# Declared Metadata

*Metadata* is optional for the Jelly language itself, but it is **vital** for the Jellycuts iOS app because it controls how a Jellycut is displayed when exported to Shortcuts.

Metadata is declared using a leading `#` followed by the tag name.

## Colour

Set the accent colour used for the exported Shortcut:

```jelly
#Color: Red
```

Available colours: `red`, `orange`, `tangerine`, `yellow`, `green`, `teal`, `lightblue`, `blue`, `navy`, `grape`, `purple`, `pink`, `grayblue`, `graygreen`, `graybrown`.

## Icon

Choose the glyph shown on the exported Shortcut tile:

```jelly
#Icon: Shortcuts
```

There are hundreds of icons. For convenience they are still listed in the legacy [icon reference](https://raw.githubusercontent.com/your/repo/main/Language_Guide/metadata.html) while we migrate the table into Markdown.

---

**Tip:** Declared metadata lines can be placed anywhere in your script, but they’re usually grouped together at the top for readability.