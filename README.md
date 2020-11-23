# 3DforTeam3

# This repository will mainly consist of these filetypes (All work with Team's version of Unity)
.blend
.obj
.fbx

# INSTRUCTIONS FOR IMPORTING TO UNITY:
< Make sure the downloaded Mesh stay in the same folder before and after importing at all times >

1) In Unity: IMPORT -> IMPORT NEW ASSET
2) Select MESH (Remember it should be any of the file type listed above)
3) Once you see the name of the Mesh (same as fileName) in the Project section, drag and drop the Mesh to Hierarchy Window
4) Ensure the Mesh is in center by looking at the Inspector Window in the Transform section and centering the vector coordinates

# NOTES:
* Make sure the downloaded Mesh stay in the same folder before Importing
* Always make sure the 3D Mesh File Type will stay in the Project's Assets Folder
* Materalize Mesh in Unity, not in Blender or any other 3D Software (Makes it easier for programmers for rendering)
* If Importing from Blender, make sure -> (Lights and Camera) are removed before saving

# BLENDER TO UNITY TIPS
To make it easier to manage meshesh, especially in a file with a lot of objects. After Importing:

1) Right click on the Collection Asset in Hierarchy Window (The name of the .Blend file)
2) Select Unpack Prefab Completely
This is equivalent to unpacking the Prefab, and keeping on unpacking any Prefab instances that appear as a result because they were nested Prefabs or base Prefabs.
https://docs.unity3d.com/Manual/UnpackingPrefabInstances.html

Any other questions, reach out to me in Discord or Twitter :)
#happygamdev
