# CT-image-segmentation-utilizing-hexagonal-lattices-and-statistical-region-merging
MATLAB code for CT image segmentation utilizing image reconstruction on hexagonal lattices and statistical region merging with connectivity twelve

This repository contains MATLAB codes to perform the following actions. 1). CT image reconstruction on square and hexagonal lattices using Fan-beam Filtered back-projection. 2). segmentation on the reconstructed images using statistical region merging for square lattices with connectivity 4, 8, and 12 and for hexagonal lattices with connectivity 12 or 6. The code image segmentation using FastFCMeans is also included.

Just need to run drFanbeamReconSegm (, drFanbeamReconSegmHex6 respectively) for CT image reconstruction on hexagonal lattices with connectivity 12 (, 6 respectively)  using Fan-beam Filtered back-projection and then segment the reconstructed images using statistical region merging. 
