# Generate Grid

A javascript function that generates a grid of elements.

## Usage

For basic usage:    
`generateGrid();`

Or add your own options:    
````
let vars = {
  parent: '.element', // defaults to document.body. Can we selector string or element node
  grid: [5, 5], // [rows, columns]
  gutter: 0,
  className: 'grid-box'
}
generateGrid(vars);
````
