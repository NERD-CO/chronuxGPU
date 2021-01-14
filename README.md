# chronuxOptimized

This includes some optimizations to allow for quicker processing of neural data.
Natural data parallelism allows for parallel execution of several functions in Chronux,
and this also makes use of Matlab's tall arrays to conserve memory.

# Forked from chronuxGPU: Instructions to enable GPU support are below.
Chronux 2.12 package with support for GPU (to speed up the computations)

The code includes a simple modification of the Chronux package (http://chronux.org/) 
to use GPU for power and coherence computations involving continuous and point binned signals.

MATLAB's GPU support should be correctly configured, and a global variable CHRONUXGPU should be set to true.

See (and run) test\GPUSpeedupTest.m for further details. 
