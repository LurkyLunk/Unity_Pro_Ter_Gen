
# Terrain Generator

This is a terrain generator project that allows you to create dynamic terrains in your Unity game.

## Features

- Procedural terrain generation
- Customizable terrain parameters
- Real-time terrain editing

## Instructions

1. Clone or download this repository to your local machine.

2. Open the project in Unity.

3. In your Unity project, navigate to the **Assets** folder.

4. Locate the **Terrain** folder within the **Assets** folder.

5. Select and drag the following scripts from the **Terrain** folder onto your terrain object in the Unity Scene view:
   - `TerrainGenerator.cs`
   - `TerrainController.cs`
   - `WaterAnimators.cs`
   - `CloudManager.cs`
   - `CloudController.cs`
   - `TextureCreatorWindow.cs`

6. Assign the required assets to the terrain object:
   - Assign a terrain material by dragging and dropping it onto the terrain object's Renderer component.
   - Attach a terrain texture to the terrain object by dragging and dropping it onto the terrain object's TerrainController component.

7. Customize the terrain parameters by adjusting the variables exposed in the **Inspector** window of the terrain object:
   - Adjust the terrain size, resolution, and scale.
   - Modify any additional parameters available in the **Inspector** window to achieve the desired terrain appearance.

8. Attach the Cloud Manager script to a game object in your scene to control the appearance and behavior of clouds:
   - Drag and drop the `CloudManager.cs` script onto a game object in the Unity Scene view.
   - Adjust the cloud parameters exposed in the **Inspector** window of the Cloud Manager script to customize the clouds' appearance, movement, and density.

9. Attach the Cloud Controller script to your terrain object to control the interaction between clouds and the terrain:
   - Drag and drop the `CloudController.cs` script onto your terrain object in the Unity Scene view.
   - Adjust the parameters exposed in the **Inspector** window of the Cloud Controller script to control how clouds affect the terrain, such as shading and visibility.

10. Attach the Water Animators script to your water object to add realistic animations:
    - Drag and drop the `WaterAnimators.cs` script onto your water object in the Unity Scene view.
    - Configure the water animation parameters exposed in the **Inspector** window of the Water Animators script to achieve desired water effects like waves, ripples, or reflections.

11. Press the **Apply** button in Unity **Inspector** to see the generated terrain in action.

## Texture Creator Window

The Texture Creator Window script provides a user-friendly interface within the Unity Editor to create heightmap noises for your terrains.

### Instructions

1. Ensure that you have already completed the initial setup steps mentioned in the previous sections.

2. To access the Texture Creator Window, follow these steps:
   - In the Unity Editor, navigate to **Window > Texture Creator** to open the Texture Creator Window.

3. Use the controls provided in the Texture Creator Window to customize and generate heightmap noises:
   - Adjust sliders, buttons, or input fields to modify properties such as frequency, amplitude, octaves, and persistence.
   - Explore different noise algorithms, such as Perlin, Simplex, or Worley, to create unique heightmap variations.
   - Preview the generated noise by clicking on the **Preview** button within the Texture Creator Window.

4. Once you are satisfied with the generated heightmap noise, click on the **Apply** or **Save** button within the Texture Creator Window to apply the noise to the terrain or save it as an image file for later use.

