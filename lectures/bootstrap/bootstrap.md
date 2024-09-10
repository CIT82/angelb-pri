# Grid System

Bootstrap’s grid system is based on 3 main components:

- **Container**: Wraps the entire grid system.
- **Row**: Defines rows in the grid.
- **Column**: Defines the number of columns in each row.

### Breakpoints:
Bootstrap's responsive layout changes based on screen sizes:
- Extra small (XS)
- Small (SM)
- Medium (MD)
- Large (LG)
- Extra Large (XL)
- Extra Extra Large (XXL)

## Creating a Basic Grid Layout

### Containers:
- **Fixed Width Containers** (`container`): Changes size based on the screen width.
- **Fluid Containers** (`container-fluid`): Fills 100% width at all times.

### Columns:
- **12-Column System**: Each row is divided into 12 columns. 

### Responsive Column Sizing:
Use `col-auto` to make a column size itself according to its content.

## Responsive Design and Breakpoints

### Breakpoint Classes:
You can specify column behavior for specific breakpoints like `col-md-6`, which will make the column 6 units wide on medium and larger screens.

### Container Classes:
`container-md` ensures a fixed width at the medium breakpoint and fluid width below it.

## Offset Columns

### Offset Classes:
These allow you to "push" columns across by a set number of units.

## Utility Classes for Spacing

### Gaps Between Columns:
Use `g`, `gx`, and `gy` to set the grid spacing.
- `g-3`: Adds gap in both directions.
- `gy-2`: Adds gap vertically.
- `gx-4`: Adds gap horizontally.

## Nesting Rows
You can nest rows inside columns for more complex layouts.

You can control how columns behave at different breakpoints.