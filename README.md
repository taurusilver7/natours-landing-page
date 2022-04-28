# Natours

- A tourism company natural tour landing page with advanced CSS and SASS.

## Build

- Learn the best way to perform a basic reset using the universal selector.
- Learn to set up project-wide font definitions.
- Learn to clip parts of elements using `clip-path`.

* Linear gradient— the direction, the color pallate (with opactity, included)

- To clip path of a picture in polygon, learn from [clip path](https://bennettfeely.com/clippy/)
- Center anything (element) with `transform, top and left` properties.
- The `transform: translate (x, y)` depends on the parent element positioning.
- The animation is effectively done with `transistion` propery and change the element propery with hover effect.
- The other variant is `@keyframes` property for animation where each moment is described.

- Pseudo-elements & pseudo-class.
  The pseudo elements of anchor are link, visited, hover..,
- The box-shadow property had attributes in (offset x, offset y, blur, color)

- replacing px values with rem. Add a refernce value as `1rem = 10px` and replace the stylesheet with corresponding rem values.
- Replace the class names with BEM naming convention.
  B - Block; a standard component meaningful on its own
  E - Element; part of a block that has no stand-alone meaning.
  M - Modifier; a different version of a block & Element.

* The CSS architecture is the folder structure for preprocessors used in the project. The `7-in-1` pattern is the most commonly used pattern for any preprocessor. It splits 7 differnt folders for partial Sass fies and 1 main Sass file for importing all other files into a compiled CSS stylesheet.

- partial Sass folders: `base/` `components/` `layout/` `pages/` `themes/` `abstract/` `vendors/`
- install node and npm packages for node-sass dependency. Create a partial sass folder and transfer all the valid css code into main.scss file.
