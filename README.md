# obsidian-sticky-notes

> Sticky Notes for Obsidian

<img src="https://github.com/dhniceday/obsidian-sticky-notes/blob/main/images/sticky-notes-readme1.png" alt="Sticky Notes in Obsidian" />

## Metadata

- different sizes [s-35, s-40, s-45, s-50, s-55, s60 - default is 30%]

- different colors [yellow, green, blue, purple, aqua, orange - default is yellow]

- align left, right and center ([eft, right, center - default is center]

- define if the first row should be bold [title - default is no title]

## In the sticky notes

- text decoration for bold and italic is deactivated

- link color is aligned with sticky note's normal text color

- highlight color is adapted to the sticky note's color

## Options in style settings

- Sticky notes colors

- Choose the font 
    - Fonts are incorporated
    - All fonts are from Google Fonts

- Text size

- Zoom on hover (still experimental and not that pretty)

CSS is a bit rough (I'm not an expert). I have created that for myself. It blends into my own Gruvbox color scheme for the Minimal theme. But all of that can be easily modified in the css.

## Examples

```
> [!STICKY]
> The default sticky 
> (takes default color from Style Settings).
```

```
> [!STICKY|yellow left]
> Sticky Note
> This one floats left
```

```
> [!STICKY|green right title]
> Sticky Note
> This one floats right and has its first line bold
```

```
> [!STICKY|blue center s-45]
> Sticky Note
> This one is centered and a bit larger
```
