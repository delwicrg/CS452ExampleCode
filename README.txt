Our project successfully follows all of the guidelines assigned to us. We have produced a realistic scene in the form of a dining room. There are chairs, a table, cups, teapot, plates, a fireplace, plant, picture frame, and chandelier that come together to make a nice dining room scene. From this list, it can be noted that the project does have at least 3 distinct pieces. In fact, it has at least 9 objects (not counting duplicates). There are also at least 4 polyhedra in this scene. The objects are loaded in using the three.js library. Further, we used the GLTFLoader to load in .glb and three.js as well to manipulate the objects. The user is able to interact with our cups and teapot using the transformations of rotations, translation, and scaling to manipulate them around the scene, including moving the pot in a way that mimics a pouring motion. There are also more than 2 lights in our scene. In particular, we have an ambient light, point light, and directional light source - meaning at least one creates a specular reflection. We also have more than 2 textures in this scene. Our table is textured to be a dark hardwood, and the fireplace is textured to be marbled. The smaller objects in the scene, such as the cups and cheese, are also textured to look as realistic as possible. 

This scene is displayed in a perspective projection, as required. In the scene, there are three objects in which you can interact with: the right cup, the left cup, and the teapot. For all three, you may scale the object (aka increase size), translate up, down, left, right and also rotate. For the rotations, the teapot rotates in the z direction to "pour" the tea while the cups rotate in the x direction as one would expect. We believe that the interactive controls are intuitive, and are described below: 

    For the left cup: 
        a   : move left
        d   : move right   
        w   : move up
        s   : move down
        q   : scale
        e   : rotate in x direction

    For the Teapot: 
        f   : move left
        h   : move right   
        t   : move up
        g   : move down
        r   : scale
        y   : rotate in z direction

    For the right cup: 
        j   : move left
        l   : move right   
        i   : move up
        k   : move down
        u   : scale
        o   : rotate in x direction

Please note that only one type of translation can occur at a time. In other words, an x and y translation can not occur simutaneously. However, scaling and rotation can be performed at the same time as a translation. Additionally, these interactions are done by setting off flags and using onkeydown to pass the event to moveKeys() which handles the behavior. Once the key is pressed, the corresponding flag is set to 1 and the interaction executes. You do not need to keep holding down the key. If you wish to stop the interaction, simply press the corresponding key again (this turns off the flag). (ex. I want to move the teapot right so I press h. I let it move then I want to stop, so I press d again)
        










Lastly, we have provided this README that describes how we implemented our scene, and it is named README.txt.
