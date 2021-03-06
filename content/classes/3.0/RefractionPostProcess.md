---
ID_PAGE: 25288
PG_TITLE: RefractionPostProcess
PG_VERSION: 2.1
TAGS:
    - PostProcess
---
## Description

class [RefractionPostProcess](/classes/3.0/RefractionPostProcess) extends [PostProcess](/classes/3.0/PostProcess)

Builtin postprocess applying e refraction texture as a postprocess

A tutorial about post process can be found here : https://doc.babylonjs.com/How_To/how_to_use_postprocessrenderpipeline

## Constructor

## new [RefractionPostProcess](/classes/3.0/RefractionPostProcess)(name, refractionTextureUrl, color, depth, colorLevel, options, PostProcessOptions, camera, samplingMode, engine, reusable)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | name | string |      The postprocess name
 | refractionTextureUrl | string |      The URL of the refraction texture
 | color | [Color3](/classes/3.0/Color3) |      The base color of the refraction (used to taint the rendering)
 | depth | number |      The simulated refraction
 | colorLevel | number |      The coefficient of the base color (0 to remove base color tainting)
 | options | number or PostProcessOptions |   
 | camera | [Camera](/classes/3.0/Camera) |      The given camera
optional | samplingMode | number |      [Texture](/classes/3.0/Texture).NEAREST_SAMPLINGMODE, [Texture](/classes/3.0/Texture).BILINEAR_SAMPLINGMODE or [Texture](/classes/3.0/Texture).TRILINEAR_SAMPLINGMODE
optional | engine | [Engine](/classes/3.0/Engine) |      The engine to attach the postprocess.
## Members

### color : [Color3](/classes/3.0/Color3)

The base color of the refraction (used to taint the rendering)

### depth : number

The simulated refraction

### colorLevel : number

The coefficient of the base color (0 to remove base color tainting)

## Methods

### dispose(camera) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | camera | [Camera](/classes/3.0/Camera) |      The given camera

