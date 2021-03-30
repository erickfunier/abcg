# Baby Yoda Projection

For Activity 2, the projection of Baby Yoda was created from an OBJ of 3D modeling.
Some resources for interacting and running the libraries have been added.

For coloring, a uniform variable was defined in the _.frag_ file, which makes it possible to change the color of the fragments at run time. Therefore, through the user interface, it is possible to color with some pre-defined colors, which are stored in vec4 in the code.
The separation of fragments is done by selecting the vertices to be drawn, therefore starting from the first element, which in this case is the scarf, the number of vertices necessary for the design was calculated, limiting the application to drawing only those triangles/ fragments with the color specified. This is done for each part of Yoda.
The user can still make Yoda's eye "blink", we only do a blink varying the colors from white to black.

A bouncing feature was also added to simulate the Yoda's fluctuation movement. (the lightsaber had to be modeled :P)

In addition to the aforementioned features, an exploded view of Yoda was added, separating the elements from the body. For this, uniform variables were added in the _.vert_, allowing the position to be modified at run time, so before drawing each part of the doll, the axis is displaced with a position obtained in simulations.
All added features can be used simultaneously.

The projection can be access in web version:

   https://erickfunier.github.io/ComputerGraphics/ABCg/baby-yoda/

   
## Authors
   Erick Funier dos Santos - RA: 11031914
   
   Paulo Ricardo Cunha - RA: 11080312

# ABCg

Development framework accompanying the course [MCTA008-17 Computer Graphics](http://professor.ufabc.edu.br/~harlen.batagelo/cg/) at [UFABC](https://www.ufabc.edu.br/).

## Author

Harlen Batagelo

## License

MIT
