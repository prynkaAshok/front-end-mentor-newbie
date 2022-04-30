<!-- # Getting Started with CSS

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!** -->

# Getting Started with CSS
## CSS GRIDS

### `Grid Container` 
Create a grid container by setting the display property with a value of `grid` or `inline-grid`. 
All direct children of grid containers become grid items.

`display : grid `
They are placed in rows by default and span the full width of a container : Block Level

`display: inline-grid`
Does not span the full width : inline

`grid-template-rows: 50px 100px`
Creats a row track for grids

`grid-template-column: 50px 100px`
Creats a column track for grids

`grid-template-columns: 1fr 1fr 2fr`
The `fr` unit helps create flexible grid tracks. It represents a fraction of the available space in the grid container

`Minimum and Maximum Grid Track Sizes`
minmax(minimunSize, maximunSize)

`Repeating Grid Tracks`
This is useful for grids with items with equal sizes or many items.
`grid-template-rows`:    repeat(4, 100px); 
`grid-template-columns`: repeat(3, 1fr);

repeat(number of items, track size)

Gutters/Gap
The `grid-column-gap` and `grid-row-gap` properties create gutters between columns and rows.
Are created only between and not at the edges
grid-row-gap:    20px;
grid-column-gap: 5rem;
SHORTHAND : `grid-gap : grid-row-gap grid-column-gap`
            grid-gap: 20px (Sets 20px for both column + row)

Positioning Items by Grid Line Numbers
`grid-row-start` : 2
`grid-row-end` :3
`grid-column-start` : 1
`grid-column-end`:2

`grid-row` :   grid-row-start & grid-row-end
`grid-column` : grid-column-start & grid-column-end
`grid-area` is shorthand for grid-row-start, grid-column-start, grid-row-end and grid-column-end.
grid-area: 2 / 2 / 3 / 3
grid-area : grid-row-start/grid-column-start/grid-row-end/grid-column-end

`grid-auto-flow: row`
`grid-auto-flow: column`

`justify-items` and `justify-self` --> align items along the row axis, and 
`align-items` `and align-self` --> align items along the column axis.
justify-items and align-items are applied to the grid container and support the following values:

auto
normal
start
end
center
stretch
baseline
first baseline
last baseline



 





