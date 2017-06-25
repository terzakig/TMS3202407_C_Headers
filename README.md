# C Header files for the TMS320LF2407 DSP Controller (EzDSP2407) 

This repository contains a set of C header files including all core and peripheral registers in the TM320LF2407 DSP controller by Texas Instruments. This controller is tranditionally programmed in assembly, primarily to exploit its special instruction set for achieving optimal performances in standard DSP operations such as convolution, Fast Fourier Transform (FFT), etc. However, there is no reason to initialize the peripherals in Assembly as this can be easily done with C. Furthermore, we always have the option of writing _C-callable assembly functions_ to implement dedicated DSP algorithms in our programs ([see this example](https://github.com/terzakig/TMS320LF2407_Examples/tree/master/AsmFunc).

The header files were developed and used in the examples of my book [**Introduction to C Programming with the TMS32LF2407 DSP Controller**](https://www.amazon.com/Introduction-Programming-TMS320LF2407ATM-DSP-Controller/dp/145658880X). The examples can be accessed in [this repository](https://github.com/terzakig/TMS320LF2407_Examples).



