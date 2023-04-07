# SAM Medical Imaging
The Medical SAM (Segment Anything Model) repository is a fork of the [original SAM repository](https://github.com/facebookresearch/segment-anything) with modifications to support object segmentation in medical imaging using DICOM files. The SAM model is a state-of-the-art object segmentation model that predicts object masks given prompts that indicate the desired object. This implementation uses SAM to efficiently produce high-quality masks from prompts for medical imaging tasks using DICOM files. It allows the user to provide box prompt via the SamPredictor class to predict masks for a given medical DICOM file.

![SAM-medical-imaging](https://user-images.githubusercontent.com/37108394/230678827-f53b684c-6bca-491f-9f67-8fd1cd642717.png)
