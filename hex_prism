// Define the hexagonal prism
module hexagonal_prism(side, height) {
// Define the hexagonal base
polygon(points = [
[side, 0],
[side/2, side * (3^0.5)/2],
[-side/2, side * (3^0.5)/2],
[-side, 0],
[-side/2, -side * (3^0.5)/2],
[side/2, -side * (3^0.5)/2]
]);
// Extrude the hexagonal base to create the prism
linear_extrude(height = height, twist = 0, slices = 1)
polygon(points = [
[side, 0],
[side/2, side * (3^0.5)/2],
[-side/2, side * (3^0.5)/2],
[-side, 0],
[-side/2, -side * (3^0.5)/2],
[side/2, -side * (3^0.5)/2]
]);
}

// Call the module to create a hexagonal prism with a side length of 30mm and a height of 60mm
hexagonal_prism(30, 20);
