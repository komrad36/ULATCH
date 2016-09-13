Fastest CPU implementation of an UPRIGHT (no rotation) LATCH 512-bit binary feature descriptor as described in the 2015 paper by Levi and Hassner:

"LATCH: Learned Arrangements of Three Patch Codes" http://arxiv.org/abs/1501.03719

See also the ECCV 2016 Descriptor Workshop paper, of which I am a coauthor:

"The CUDA LATCH Binary Descriptor"

Note once again that this is an UPRIGHT LATCH, a.k.a. ULATCH. A fast rotation- and scale-invariant version is in the works.

This implementation is approximately 16 times faster than OpenCV.

All functionality is contained in the file ULATCH.h. 'main.cpp' is simply a sample test harness with example usage and performance testing.