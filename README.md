# MatrixManipulationInTexture
MatrixManipulationInTexture in webgl shader

A quick example on Matrix manipulation inside RGBA encoded textures in WEBGL

this example shows how matrix can be encoded in RGBA channels and used for calculations in Fragment channel

the first Canvas is the input texture

the second canvas is the output texture with Matrix manipulation


a simple addition is used on R channel and G channel and results saved in R channel, results can be retrieved from resulting canvas 

complex multiplications will have to encode result in 32 bit floating point adn saved in all vec4 x,y,z,w components

this is a rudimentary use case on how GPU processing can be used to accelerate common CPU-intensive tasks utlizing shader GLSL languages

