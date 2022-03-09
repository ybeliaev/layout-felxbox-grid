# Flexbox and grid examples
## For Responsive CSS Layouts

### :boom: features FLEXBOX project:
1. `flex-flow `
   > The flex-flow CSS shorthand property specifies the direction of a flex container, as well as its wrapping behavior.
2. `object-position`
   > https://www.w3schools.com/cssref/tryit.asp?filename=trycss3_object-position
3. `display: flow-root` 
   > flow-root clears the float 
4. `shape-outside`
   > In Firefox, you can draw with shape-outside in browser tools 
   >
   > :exclamation: PNG image specially to work on its transparent area
5. Responsive Images
   > https://www.responsivebreakpoints.com/  -  there is the generator for optimal responsive image dimensions
### :boom: features GRID project:
1. I can not use positioning
   > figure is the parent for img and figcaption gets `grid-template-rows: repeat(3, auto);`
   >img have `grid-row: 1/3;`
   > figcaption gets `grid-row: 2/3;` NOT `grid-row: 3/3;`
2. `auto-fill` 
   > как бы говорит “я автоматически заполню строку таким количеством колонок, как это возможно с учетом заданной ширины”.
   >
   >`grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));`
3. `auto-fill` vs. `auto-fit`
   > with `auto-fill` the element starts at the minimum size
   >
   >with `auto-fit` the element starts at the maximum size
   >
   >https://codepen.io/rachelandrew/pen/dpYzZq