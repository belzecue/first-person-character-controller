# Overview
A simplified, stripped down version of the Book of the Dead player controller, including a version that incorporates a Cinemachine camera. Useful for quick prototyping and first person narrative games. Specifically, the complex (but admittedly cool) footstep and depth of field features have been removed. Maybe I'll add simpler versions of these features at a later date.

# Prerequisites
## Post Processing
Use a project template that includes post processing, or install the [Post Processing package](https://docs.unity3d.com/Packages/com.unity.postprocessing@2.1/manual/Installation.html) from the Unity Package Manager. Alternatively, you can remove the **PostProcessingLayer** component from the **Main Camera** GameObject. This will likely display as "missing script" if you do not have the Post Processing package installed.

## [Optional] Cinemachine
In order to use the Cinemachine version of the character controller, be sure to first install the [Cinemachine package](https://unity.com/unity/features/editor/art-and-design/cinemachine) using the Unity Package Manager.

# Installation
Download the **First.Person.Character.Controller.unitypackage** file from the [releases section](https://github.com/dantogno/fps-controller/releases) and run it to import into your currently open Unity project, or use the [**Assets > Import Package**](https://docs.unity3d.com/Manual/AssetPackages.html) option from the Unity menu.

# Use
Be sure to disable or remove any additional main cameras and audio listeners from your scene.

## For Cinemachine
Add the **First Person Character Controller with Cinemachine** prefab to your scene

## No Cinemachine
Add the **First Person Character Controller NO Cinemachine** prefab to your scene.
