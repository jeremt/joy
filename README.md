# joy (WIP)

UI components based on emotion.

## Box

This component allows to handle layout properties (based on flexboxes).

```js
<Box direction="y" width="100%" height="100%" align="center" distribute="center" />
```

| Property    | Values              | Description    |
| ----------- | ------------------- | -------------- |
| direction   | x, y                |                |
| width       | 50px, 100%, etc.    |                |
| height      | auto, 400px, etc.   |                |
| grow
| align
| shrink
| direction
| distribute
| margin
| padding
| overflow
| spacing


## Text

Inerits from Box. Add some typograhy related properties.

```jsx
<Text fontSize={1.2} color="theme.foreground" />
```
