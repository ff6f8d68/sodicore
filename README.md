# sodicore

sodium but support for core shaders in resourcepacks

## How to write shaders for sodium?
Sodium shaders are similar to core shaders, but not the same.
The base Sodium Shaders can be found [here](https://github.com/CaffeineMC/sodium-fabric/tree/dev/src/main/resources/assets/sodium/shaders).
Sodium Shaders must be in `assets/sodium/shaders` directory. But you can `#import` files from
`assets/minecraft/shaders` using the `#import` directive. The following code will include
the file `assets/minecraft/shaders/include/test.glsl`:
```glsl
#import <minecraft:include/test.glsl>
```
