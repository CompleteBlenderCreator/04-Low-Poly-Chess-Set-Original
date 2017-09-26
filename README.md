### Section 4 Introduction ###

Mikey and Ben introduce this section.

### Your Section 4 Assets ###

+ This is the Lecture where you will find all of the files you will need to complete the Section.
+ Please Download your Asset Pack now.
+ Your files will come in a Zip file ready for extraction to your computer.

### Managing A Larger Project ###

+ Learn how to manage a larger project.
+ Store your files for quick recall.
+ This is just a suggested workflow.

### Planning Our Project ###

+ Check out the design specs of a chess board.
+ Design our chess board using that info.
+ Decide on a working scale.
+ Play about in Blender to get it feeling right.

### Mesh Objects and Mesh Data ###

+ Start creating our chess board
+ Replace a cube mesh object’s mesh data
+ Demonstrate the grid mesh option too

### Re-centring Your Objects ###

+ How to centre your model in the view.
+ Learn how to control an objects origin.

### Creating A Standard Asset ###

+ Chose a style of chess set.
+ Decide on construction method.
+ Start creating our asset.

**Construction Method**

+ Split our models in two.
+ Make a standard base asset that we can work from for all the other models.

### Using The Bevel Tool ###

+ Box model the chess piece base.
+ Using the bevel tool to round off our sharp edges.

### Appending Or Duplicating ###

+ Learn when you would duplicate an asset model.
+ Choose when appending would be better.

**Duplicating Vs Appending**

+ Appending picks out key parts of a blend file.
+ Other Scene data would have to be appended separately.
+ Duplicating would be _exactly_ the same as the original file with everything intact.

### Bridging Edge Loops ###

+ Learning the power of bridging edge loops.
+ Oops our pawn is lovely but has too many polygons!

### Finish the Low Poly Pawn ###

+ Open up the new LowPoly base piece.
+ Make sure you are working on the _new_ Blend file.
+ Be mindful to keep the top sphere 8 segments.

### Managing The Chess Scene Assets ###

+ Decide how we can manage our materials.
+ Creating materials in _one_ blend file.
+ Each project will have a different way of handling materials depending on it's size and scope.

**Materials In Our Project** 

+ 32 Pieces: Black & White
+ Board: Black & White & Wooden Surround
+ 5 Materials in the project.
+ We're going to assign materials in a Chess Scene Blend file.

### The 3D Cursor and Origins ###



### Selecting Hidden Geometry ###

+ Learn how to select geometry that isn't visible.
+ Two straight forward ways, 
    1. Switch view port shading to wireframe.
    2. Toggle 'Limit selection to visible'.
+ Build the rest of the Bishop.

### Boolean Modifier ###

+ Experiment with a boolean modifier.
+ Understand how to apply it to our model.
+ Can been used constructively and destructively.
+ It can work in edit mode.
+ Real time and live!

### An Introduction To Empties In Blender ###

+ Introducing the concept of an empty.
+ An empty is a null object, and has no geometry.
+ They can be used as a handle to control objects.
+ Used as a parent object for a group of objects.
+ Many other uses.

**Keeping It Lean**

+ Append the bishop into our chess scene.
+ Check everything is right proportion wise.
+ Start filling up our board, creating the white pawns.
+ Link duplicate our bishop and pawns.
+ Managing our models in this scene.

### Parent and Child Objects ###

+ See how parents can group together objects, their children.
+ Create a hierarchy which is easy to navigate.
+ We'll be using this to logically group our pieces.
+ Parent>Child>Grand Child>Great Grand Child!

### Zoom To Mouse & Rotate Around Selection ###

+ Great for working around more complex scenes.
+ We're changing the user preferences.
+ Demonstrate both zoom to mouse and rotate around selection.
+ Other view options available.

**View Options**

+ View>View Selected (NumberPad .)
+ View Dolly: Ctrl + Shift + Middle-Mouse / Ctrl+ Shift + +/-.
+ Walk/Fly Mode: Shift + F.

### Lighting in Blender Render ###

+ Understand that lamps apply to **Blender Render**.
+ Light is handled differently in Cycles.
+ Adjusting lamps properties and seeing it's affect.
+ We will switch to rendered mode in the viewport shading options to see this effect.

Further Reading on Blender Render Lighting:
+ http://wiki.blender.org/index.php/Doc:2.4/Manual/Lighting/Lights/Light_Attenuation

### Hiding Un-Needed Objects. ###

+ Discover it is useful when working on larger and more complex assemblies or scenes.
+ Control whether you are hiding groups of objects as well as individuals.

### Diffuse and Specular: Blender Render ###

+ Need to understand these for getting rendering right.
+ Looking at the two in isolation.
+ Combining them to see the effect.
+ Still using Blender Render.

**Diffuse vs Specular Reflections**

+ Both are types of reflection.
+ Diffuse is when Light scatters as it hits a surface.
+ Specular is direct reflection of the light to the viewer.
+ Materials are often a mix of the two.

### 23 Using An Image As A Texture

+ Show you how to add a texture to your material.
+ Reinforce the defuse and specular settings.
+ Model the board surround.
+ Apply a texture to the board surround.
+ (Updated 26/09/2017)

### Using Procedural Textures ###

+ Introduce procedural textures.
+ Apply some to the chequers on the board.

### Quads Vs Triangles and Ngons ###

+ Better overall to make models using quads.
+ Explain what they are.
+ Whatever you use- it is being converted back to triangles in the background.
+ Watch out making things non planer…

### Non Planar Geometry ###

+ Only happens with quads and NGons.
+ Rendering & Exporting **_always_** converts geometry into triangles.
+ Lose control over the rendering.
+ You cannot always see this in the 3D window.
+ Makes a huge difference with flat models and flat shading.

**Triangles and NGons**

+ If your model comes to a point you might need a triangle.
+ When sub dividing part of you model you are likely to create an NGon elsewhere.
+ You will break loops when doing this.

**Solutions**

+ Good mesh topology from the beginning.
+ Be lean and check your model through.
+ Turn on mesh analysis (not 100%).
+ Manually make face(s) Planar again. Normal, SZZ0.

### Edge Rings ###

+ Learn about edge rings.
+ How they help you manage your geometry.
+ Definition: A series of edges which are not directly connected, but share faces.

### The Mirror Modifier ###

+ How to setup and use the Mirror modifier.
+ Start creating our Knight.

### The Edge Split Modifier ###

+ Focus on creating a free form model.
+ Ensuring faces are not triangulated when being created to keep with our style.
+ Introduce the edge split modifier.
+ This is the basis of organic modelling.

### Modelling Challenge - Rook ###

+ Start the Rook from the “LP Chess Piece Base” we made earlier.
+ Remember to use the reference material for a rough scale and shape guide.

### Modelling Challenge - King ###

+ Suggest using the queen as a starting point.
+ To make the King the right size by out specs, a base of 4 > 4.5 is a scale of 1.125.
+ Make the king your own, and have fun.

### Setting Up A Camera For Rendering ###

+ Learn about camera placement.
+ They're a directional object.
+ Overview of the camera settings.
+ You can have more than one camera, but only one active camera.

### Exporting Your Chess Model ###

+ Tidy our folders for future access.
+ Export your model(s) as an FBX.
+ Import .FBX into Unreal and Unity game engines.
+ Opening Blender models in Unity 5.
+ About exporting textures and materials.

### End of Section 4 ###

End of the Chess Section.
