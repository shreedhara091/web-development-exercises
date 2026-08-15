# Exercise 2 - CSS Paragraph Styling

CodeWithHarry Web Development Exercise 2.

## Question

Write HTML and CSS code to style the paragraphs inside a `<div>`.

The given HTML contains multiple `<div>` elements, and each `<div>` contains paragraphs.

### Requirements

- The first paragraph inside each `<div>` must have:
  - Background color: Yellow
  - Text color: Red

- The other paragraphs must have:
  - Background color: Blue
  - Text color: White

- Do not change the given HTML structure.

## Concepts Practiced

- CSS selectors
- Element selectors
- `div p:first-child`
- Background colors
- Text colors
- Styling elements using CSS

## CSS Used

```css
p {
    background-color: blue;
    color: white;
}

div p:first-child {
    background-color: yellow;
    color: red;
}