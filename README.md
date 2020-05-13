#Introduction- 
This report will discuss the use of Rendermonkey and GLSL to produce a pirate treasure cove cave effect. 
Cave walls- 
 
The walls are created using the cube model and the floor and roof are made using 2 different terrain models. The mapping type that I have used for each of these walls is the normal bump mapping to provide a bumpy look to each wall. 
Treasure chest- 
 
The treasure chest has been created using the cube model again but uses a wooden texture to give it an authentic feel, it has been placed in a way that it looks buried by the pirate whose treasure it is. This uses a bump map too to allow for a more in depth look. 
 
#Animated wood fire- 
 
The animated wood fire is made from 3 different passes, 2 for the pieces of wood and 1 for the fire itself. The fire has been implemented by a particle system, using the quad array model to ensure it is always facing the camera, with a flame as its particle. This was to create a semi realistic flame to use as fire. 
Rusty metal teapot- 
 
The teapot uses the teapot model and uses a range.bmp for the texture to give a rustic look. The colour has also been modified as well as the lighting using the normal mapping method to give a more rusted dirty look to give a very dirty feel to the cave. 

#Animated pond water- 
 
A shallow pool of water has been implemented using the screen aligned quad to produce an animated reflective pool of water. The colour has been edited to increase the authenticity by darkening its colour to a murky brown to show how dirty the cave is. It uses a cubemap to provide a reflection on the surface. 

#Flying avatars- 
 
Two moving avatars have been implemented, the teapot whose wings act to give a feel of a flying animation and the skull whose wings have been morphed to move as well but for this avatar to go up and down the Y-axis. They are both implemented using angles and time to deform the wings of each avatar. 
 
#Torches- 
 
These torch effects are created using 2 passes each, 1 for the particle fire and another for the torch wood. They do not produce the local illumination but are animated like the bigger wooden fire. 
Dino ghost object- 
 
The Dino Ghost object was created using the Dino model and a screen aligned quad with the corona texture to provide a glowing effect. The glowing effect used here is coloured red to give a sinister feel to the cave to further state that it is a pirate cave. 

#Ghost fog- 

The ghost fog is implemented using a similar particle effect to the fires with slight changes to sqread timing and size. This allows the whole bottom of the cave to be covered by this mysterious fog and obscure the cameras vision to give a more realistic feel when look into the cave. 

#Own effects- 
 
A platform, step, cannonballs and gold coins have also been implemented to give more of a feel of a habited pirate cave. The platform and step are implemented using the same method with different sizes give a different floor level in the cave. The gold coins are implemented using the disc model to produce a coin like shape before the colour is change to a dirty yellow/gold to give an old look to them. The cannonballs are implemented using the sphere model with changes to the colour to produce a black look of a fresh cannon ball. 
