## Driver Benchamrks in LLVM 12
For each driver, the boundaryFiles dir contains the interface information. 

* exported_funcs contains all the callback functions exported by the driver. 
* imported_funcs contain all the kernel functions imported by the driver.

To test interface related analysis, run on the functions provided in the exported_funcs, as they are interfaces provided by the driver and kernel pass data through the function parameters. 
