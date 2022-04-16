# b3dsdf

b3dsdf is a collection of 2d signed distance functions and operators nodegroups for Blender 2.83 or above. Also available as an addon which adds a menu in the shader editor. These nodegroups are manually translated from code with help of sources listed under [References](https://github.com/williamchange/b3dsdf#references)

All nodegroups were already marked as assets in the .blend file which can be used with the asset browser in 3.0 by adding it as an asset library.

## Available Nodegroups

A list of available nodegroups can be viewed in the [shader_nodes.json](https://github.com/williamchange/b3dsdf/blob/master/shader_nodes.json) file. There's currently 42 nodegroups.

![SDF_Nodegroups](https://user-images.githubusercontent.com/830253/163684246-2b791eda-62d5-4ac1-9f4c-a1ab874e473e.png)

## Planned / work in progress

- sdUnevenCapsule
- sdHorseshoe
- sdRoundedCross
- sdEgg
- sdEllipse
- sdBlobbyCross
- sdSquareStairs
- sdStairs
- sdPolygon (16 Points)

## References

1. [Inigo Quilez's 2D Distance Functions](https://www.iquilezles.org/www/articles/distfunctions2d/distfunctions2d.htm)
2. [Inigo Quilez's 2D SDF Primitves Shadertoy playlist](https://www.shadertoy.com/playlist/MXdSRf)
3. [Erindale's Toolkit (Add menu logic)](https://erindale.gumroad.com/l/erintools)
4. [D6464 Blender SDF patch (Vector operators)](https://developer.blender.org/D6464)
