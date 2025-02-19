# Level Surfaces: an OpenSCAD based 3D surface grapher
## with special 3D printing functionality

Level surfaces helps you graph and understand 3D functions. You can not only render 3D functions, but you can export surfaces to STL files. 

### Demo
![frame00001](https://user-images.githubusercontent.com/31556469/67651733-86987c80-f8ff-11e9-9bec-b753b0f5782d.png)
![hypberbolalq](https://user-images.githubusercontent.com/31556469/67654150-d2502380-f909-11e9-86e8-9986d2392e27.gif)


## FAQ


### How does it work?

The rendering system uses a  [Marching Cubes](https://en.wikipedia.org/wiki/Marching_cubes) algorithm to take points from the function and translate them to a 3D model. This works by extracting data points from the function and then creating a polygonal mesh field based on the cube's intersections.


### About rendering algorithms.

Several algorithms for tracing 3D objects exist. [These methods](https://en.wikipedia.org/wiki/Isosurface) (sphere tracing, marching cubes, level set, dual contouring, etc) extract points to express density or orientation of points.
