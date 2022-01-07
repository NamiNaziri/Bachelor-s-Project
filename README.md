# Analysis of the animation graph in Unreal Engine and implementation of an animation system using OpenGL 

Computer animation is the process used for digitally generating animated images. Modern computer animation usually uses 3D computer graphics to generate a three-dimensional picture. In most 3D computer animation systems, an animator creates a simplified representation of a character's anatomy, which is analogous to a skeleton or stick figure. In human and animal characters, many parts of the skeletal model correspond to the actual bones.

In the first phase, the animation graph will be examined in Unreal Engine. The animation graph is used to evaluate a final pose for the Skeletal Mesh for the current frame. This graph is used to sample, blend, and manipulate poses to be applied to Skeletal Meshes by the Animation Blueprints. We will examine the graph and the algorithm it uses at this stage.

In the second phase, the skeletal animation system is implemented from the ground up, based on the methods obtained. This step has four objectives. The first objective is to render a skeleton in a 3D environment created using OpenGL. As part of this step, we will write a program in C++ that will display the animation created by key frames. The next step will be to show motion-capture animations. As a third objective, skinning methods are used to add a mesh to the skeleton. Ultimately, we want to use the animation blending method to blend together different animations.
