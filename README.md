



# UdonPlatformHook
 
 ## Requirements
 
 * [VRCSDK3-Udon](https://vrchat.com/home/download) v.2021.08.04.15.07+
 * Unity 2019.4.29f1
 
 
Prefab that functions as a drag and drop solution for making players correctly follow any moving Platforms, Vehicles and GameObjects in your scene when standing on them. Makes players functionally behave as if they were parented to the game object they are standing on. Players will seamlessly move and teleport with colliders they stand on. Behavior can be enabled or disabled based on layers. 


## Usage

Drag the prefab into the root of your scene to use. You only need one. Set moving colliders to layer 11(Environment) or manually assign layers in the particle collision settings.

## Example
Typically the player is unable to follow moving colliders automatically and will remain stationary, with this prefab the player will follow collider movement and rotation.

https://user-images.githubusercontent.com/74171114/130368388-7721e8c7-ec4a-403f-b4bc-e561a8ad06fb.mp4

## Other

Doesn't currently work with CyanEmu due to it not supporting origin tracking. Testing will need to be done in game.
