# AdvancedCAD

## Skateboard

For this assignment, I had to use Onshape to create a CAD skateboard. This project included multiple parts that had to then be assembled. After assembly, I went back and improved some of the parts to make them more realistic.

[Onshape Document](https://cvilleschools.onshape.com/documents/94688fa6ba9b8501a3c821bf/w/0247a133f9e5e94942ede10e/e/4af12767c85af2d5f4d7c289)

### Table of Contents
* [Deck](#Deck)
* [Trucks](#Trucks)
* [Wheels and Bearings](#Wheels_and_Bearings)
* [Assembly](#Assembly)
* [Bending the Board](#Bending_the_Board)
* [Realistic Trucks](#Realistic_Trucks)

### Deck

<img src="Images/deck.png" alt="deck.png" width="450" height="200"/>

[Image Cred](https://github.com/afriedm49)


The deck was the simplest part of the board to complete. I had to make a rectangular sketch with a circle at each end and put tangent constraints at each end to keep the circles aligned. Next, I added a rectangle to use as a pattern for screw holes and I created another one by making it symmetrical across the center line. I used Onshape's hole tool to add holes at each corner of the two rectangles, which made it easy to add countersunk holes. I then added a fillet around the edge to give the board a smoother look. The most important parts that I learned here are first that it is easier to constrain than it is to dimension everything, and second that the hole tool is much easier to use than creating a sketch and removing it for each screw hole. 

### Trucks

<img src="Images/truck.png" alt="truck.png" width="450" height="200"/>

[Image Cred](https://github.com/afriedm49)

For the truck, I first extruded part of the baseplate from the hole pattern rectangle that I already created. I then sketched the rest of the baseplate and hanger from the right plane. After extruding those parts, I created the bushing from a plane of the baseplate, and the connecting tab of the hanger from the surface of the bushing. The most important part of this step was learning how to use geometry from other sketches and objects. This allowed me to build on what I already had, rather than recreating each and every piece each time I needed to sketch something. 

### Wheels_and_Bearings

<img src="Images/wheelAndBearing.png" alt="WheelAndBearing.png" width="300" height="300"/><img src="Images/wheelAndBearingSketch.png" alt="WheelAndBearingSketch.png" width="300" height="300"/>


This part of the assignment was pretty straighforward. The most important part was to do a revolved extrusion instead of a normal one. This makes it much easier due to the circular shape of the object, and it makes it much easier to come back later and change the dimensions if necessary. The bearing could just be sketched within the wheel after it was extruded and the middle of the bearing could be set in by sketching a new circle and cutting away part of the bearing.

### Assembly

<img src="Images/skateboard.png" alt="skateboard.png" width="300" height="200"/><img src="Images/skateboard2.png" alt="skateboard2.png" width="300" height="200"/>

After creating all the necessary parts, I assembled them into the final product. This was fairly easy to do. All of the mate connectors that I needed were already there, so I just had to snap the pieces together. I also had to go in the Onshape standard parts libray and add in screws and nuts for the trucks and wheels. For this part, it is neccessary to make sure you use the exact right parts, otherwise they will not fit correctly.

### Bending_the_Board

<img src="Images/deckSketch.png" alt="deckSketch.png" width="300" height="200"/><img src="Images/deckBent.png" alt="deckBent.png" width="300" height="200"/>

For this part of the assignment, I didn't have to change the original sketch. I actually used the split tool to separate the semi circles at the end from the main rectangle. Then, I used the move tool to angle the ends up and I used fillets to smooth out the bend.

### Realistic_Trucks

<img src="Images/truckRealisticSketch.png" alt="RealisticTruckSketch.png" width="300" height="200"/><img src="Images/truckRealistic.png" alt="RealisticTruck.png" width="300" height="200"/>

For this final modification of my skateboard, I went back into the sketch for the truck and altered the shape of it to make it more realistic. In order to do this, I left the lines that other pieces were constrained to, and I redrew the rest of the lines at angles. Afterwards, I had to alter the position of the hanger and the thickness of the bushing to account for the different dimensions. One thing I had trouble with was trying to constrain the sketch for the tab coming off the hanger. In order to resconstrain it, I had to Use the circle on the end of the hanger on the tab sketch and then draw a midline to attach the sketch to. Normally, there would be a midpoint to use, but for some reason I could not find it.
