# Dataset Description
Each example in the dataset contains the following: 
• image: Multi-spectral satellite image as a 3D array with shape [16, H, W] 
  – 16 spectral channels for a given image. 
  – Values are float32 type, in the range [-3, 3] 
  – Height and width of the corresponding image. 
• label: Corresponding label/mask as a 2D array with shape [H, W] 
  – Values are uint8 type, typically binary (0 or 1) 
• i: Spatial coordinate i (int32) 
• j: Spatial coordinate j (int32) 
• start time: Start time of the satellite observation (string) 
• end time: End time of the satellite observation (string) 
• ind: Index within the original data array (int32) 
• size: Resolution size of the image (int32)
