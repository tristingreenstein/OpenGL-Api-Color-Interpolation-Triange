# OpenGL-Api-Color-Interpolation-Triange
The objective of this homework is to give you a hands-on approach to OpenGL and the basics of Computer Graphics.

Your assigned to create a triangle that will interpolate its vertices between the colors of RGB.

You will need to read chapters/sections 4, 5 and 6 from the book Learn OpenGL Book.pdf in order to complete the assignment.

Your vertex data and attributes are configured as such:


       // set up vertex data (and buffer(s)) and configure vertex attributes
       // ------------------------------------------------------------------
       float vertices[] = {
              // positions         // colors
               0.5f, -0.5f, 0.0f,  1.0f, 0.0f, 0.0f,  // bottom right
              -0.5f, -0.5f, 0.0f,  0.0f, 1.0f, 0.0f,  // bottom left
               0.0f,  0.5f, 0.0f,  0.0f, 0.0f, 1.0f   // top
       };

The top vertex starts out Blue, the bottom right starts out Red, and the bottom left starts out Green. You will be interpolating the vertex colors between the R, G, and B spectrum for each vertex.
