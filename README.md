# Among-Us-Crewmate-RISC-V-gif
RISC-V assembly code to animate an Among Us crewmate walking GIF to run on the CPE333 pipelined OTTER via any display with a VGA input. 
All frame data and assembly code can be found in the ".s" file provided in this repository. For any machine code produced from the assembly code to run properly, the VGA 80x60 module provided by Professor Joseph Callenes must be interfaced with the OTTER. To run the program, simply use the GCC tool chain to compile to the code into machine code, and then paste that code into the OTTER mem file.

Frame data processing was done using a tool created by Trevor McKay which can be found in his repository, trmckay/riscv-kernel-convolution in the image_assmblr folder (https://github.com/trmckay/riscv-kernel-convolution/tree/master/image_assmblr)!

A link to a demo of the GIF running on the VGA display via the OTTER can be found here: https://www.youtube.com/shorts/ZL4vtLfvV5I

The GIF used for the animation can be found here: https://www.gifcen.com/among-us-2/

Thank you for checking out the Among Us Crewmate RISC-V GIF for use with the OTTER!
