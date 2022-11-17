Readme WebGLCube

The assignment is to create a cube which rotate in a single direction. 

Adjustments to the inicial cube need to be made in order to change colors
    1. The task is to have one solid color per cube face. Hence, the Game.razor file in the section 'code' need to be modify.

    2. The principal area which will be modifed are the cube arrays for the vertice. There, we redefine the 12 vertices point's location with their values. Later, we need to ideantify each position to a vertice point. 

    3. Only when this has been done and we've checked it works properly, we can start working with the RGB color in the '0.0f' format. As easy as choose one color per face a repeat the same color code in each of their vertice. Later, you repeat this process 6 times (each face) with a differen RBG color each.

    4. To finalize, you sav ethe project and run it one last time (dotnet run). The cube should rotate and the colors should be rendered 