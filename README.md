# joy (WIP)

UI components based on emotion.

## Box

This component allows to handle layout properties (based on flexboxes).

```jsx
<Box direction="y" width="100% 100px|sx:100%" height="100%" align="center" distribute="center" />
// or
<joy.box margin="10px 0" xl-margin="20px 0" />
```

### Properties

- as (the element : h1, div, main)
- direction (x, y)
- width CSSSize
- height CSSSize
- grow true/false
- align
- shrink true/false
- direction
- distribute
- margin
- padding
- overflow : "auto" | "none" | "visible"
- position: "absolute" | "relative"
- spacing
- opacity
- wrap true | false
- onClick (automatically adds cursor pointer when onClick is defined)

## Text

Inerits from Box. Add some typograhy related properties.

```jsx
<Text fontFamily="theme.text.font" fontSize="theme.text.legend" color="theme.color.foreground" />
<Text color="theme.color.primary" width="100px 100%" height="100px" />
```

### Properties

- color: CSSColor | theme
- fontSize (in rem)
- fontWeight
- textAlign
- lineHeight
- letterSpacing
- selectable
- emphasis
- linesCount

## Icon

- Automacilly import icons with glob ??
- use <i>

## Button

More generic approach ?
Handle pseudo states ?

## Input, TextArea, etc.

TODO

## Theme ???

- Maybe rename some stuffs, make it easier to use?
- Handle "monochrome" colors as levels (ex dark0, dark1, dark2, and light0, light1, light2)
- Handle sizes (text sizes, padding???)

## Questions ?

- handle background / transform ?
- handle hover/active states ?

