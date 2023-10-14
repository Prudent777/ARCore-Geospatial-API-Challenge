# ARCore-Geospatial-API-Challenge-V1
 ARCore Geospatial API Challenge -Make the world your canvas with the ARCore Geospatial API!
 
# BUILD WORLD-SCALE, IMMERSIVE AR EXPERIENCES! 
Augmented reality (AR) blends the physical and digital worlds - transforming the way you shop, learn, create, and experience what’s around you. With Google’s recently announced ARCore Geospatial API, developers and creators can now create and publish AR experiences in over 100 countries, without ever having to be there. This allows you to create new world-scale use cases across gaming, education, entertainment, and more.

We are excited to announce the ARCore Geospatial API Challenge, our latest competition where we invite you to use the ARCore Geospatial API to create a unique application for a chance at winning one of 12 available prizes, ranging in value from $1,000 to $12,000. Whether you choose to develop a unique AR experience in navigation, create an AR multiplayer game, or integrate Geospatial API in new ways, we want to see what creative and interesting AR applications you can make.

In addition to awarding 1st through 3rd place prizes, we are offering special bonus prizes in the following categories: navigation, gaming, entertainment, and local discovery. To get started, check out the Resources section for documentation links, more information on Geospatial API, and examples of use cases in the bonus prizes categories. Plus, if you are interested in trying out ARCore APIs that are not publicly available, follow the steps to apply to the ARCore Geospatial API Early Access Program (EAP). 

Be sure to share your creations on Twitter and tag us using the hashtag #GeospatialAPIChallenge for a chance to be featured on @GoogleARVR! 

We’re excited to see what you create for the world ! 

#PROJECT DESIGN 
 Desing Parts
 
API: Application Programming Interface. The API is a set of functions that aim to be
an intermediary between two programs. The first program offers services to the
second program through the API. In our case, the game client makes requests to
the server to get and post data. The API represents this set of requests, it is the
entry point of the client to get data from the server. The purpose of this
architecture is the client does not need to know how the server works to get the
information.


Build: The build is the package that contains the final game compiled and playable
on the computer. For example, on a standalone PC game, the build is the .exe
file you double-click on to open the game. A build for Android consists in a
“.apk” package that can be installed on Android devices. In this document, we
opposed the “built version” to the “editor version”, which corresponds to the
whole unity project developers are working on.

HUD: Head-up display. The HUD is the group of information of the interface displayed
at the screen borders during the game (its position is different from one game to
another). The HUD often contains the main information about the player status.
In EnerGAware, the HUD shows the player money, energy, happiness points, etc.


Mesh: A mesh is just a 3D model, regardless of any texture, material or script. It is made
with a 3D modeller tool (Maya, 3Ds Max) and composed of a number of faces.
The most faces a mesh has the most graphic instructions requires to display it. This
is why a mobile game must be “low polygon”. This means all meshes contain the
minimum faces and all the small details (for example, buttons on a microwave)
will be painted directly on the texture that will be applied on the object.
Shader: Each object of the game has a material. Materials are definitions of how a
surface should be rendered, including references to textures used, colour tints
and more. The available options for a material depend on which shader the
material is using. 


Game Sample Output

https://user-images.githubusercontent.com/92072920/206423156-810401bb-c3f0-4ab8-bc59-98a2ae3a2f40.mp4
