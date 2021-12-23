### Landing Webpage with advanced 7-1 CSS Architecture.

The detailed readme will be written soon.

#### Responsiveness: Basic responsiveness design principles
  - fluid layouts
    - To allow webpage to adapt to the current viewport with ( or even height )
    - Use % ( or vh / vw) unit instead of px for elements that should adapt to viewport (usually layout)
    - Use max-width instead of width
  - responsive units
    - Use rem unit instead of px for most lengths
    - To make it easy to scale the entire layout down (or up) automatically
  - flexible images
    - By default, images don't scale automatically as we change the viewport, so we need to fix that
    - Always use % for image dimensions, together with the max-width property
  - media queries
    -  To change CSS styles on certain viewport widths (called breakpoints)


#### Layout types:
  - Float layouts:
    - The old way of building layouts of all sizes, using the float CSS property. Still used, but getting outdated.
  - Flexbox:
    - Modern way of laying out elements in a 1-dimensional row using floats. Perfect for component layouts.
  - CSS Grid:
    - For layout out element in a fully-fledged 2-dimensional grid. Perfect for page layouts and complex components.