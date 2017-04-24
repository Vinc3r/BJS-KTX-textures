# BabylonJS & compressed textures

This is a test scene to know if a device support ktx textures, and if so, what type.

* You can check [babylonJS documentation](http://doc.babylonjs.com/tutorials/multi-platform_compressed_textures) about KTX textures,
* [babylonJS playground](http://www.babylonjs-playground.com/#1SCH7H#4) which using these textures,
* [Online demo](https://www.nothing-is-3d.com/tools/babylonJS/ktx-textures/) available on my website,
* [Dedicated forum post](http://www.html5gamedevs.com/topic/29114-using-compressed-textures-now-with-a-playground/),
* [non-exhaustive list](https://github.com/Vinc3r/BJS-KTX-textures/wiki) of tested hardware.

Feel free to contribute.

## How to generate custom textures

### Easy but manual way

* launch PVRTexTool ([download link](https://community.imgtec.com/developers/powervr/))
* open your image source file (png, jpg, tga, whatever)
* Edit menu > Encode
* Tweak settings, example : 
    * Group/API = OpenGL ES 1
    * highlight selection = ETC1
    * ETC Encoding Mode = Fast
    * Generate MIPMaps checked
    * Vertical Flip checked
* Save your file as _.ktx_

### Batch way...

..._but-I-don't-know-yet-how-to-customize-it_ is to use .bat files from [babylonJS doc]((http://doc.babylonjs.com/tutorials/multi-platform_compressed_textures).
