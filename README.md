# Stitch Fix Final Project
# Final-Project
DMA Final Project

Smartfit-master folder has all the code and stage-wise results in result folder
### URL: http://3.88.222.34:5000/

For the url login:

### Username: sayali

### Password: sayali@123

### Input image name: input.jpg

Note: the demo is tested for just below images. For testing on different images you need to go through testing the code for rest images as well

### Claat Link: https://codelabs-preview.appspot.com/?file_id=1fMRRFxcZKDVJ9accxqPZzuuEMwbejhY74bV6azSq7GI#0

<img src="Untitled Diagram.jpg">
# Virtual Wardrobe
### A virtual fitting room service for StitchFix!
<p float="left">
  <img src="SmartFit-master/inputs/example_person.jpg" width="256" hspace="20"/>
  <img src="SmartFit-master/inputs/example_clothing.jpg" width="256" hspace="20"/> 
  <img src="SmartFit-master/output/example_output.png" width="256"/> 
</p>

* [Important Note](#important-note)
* [Requisites](#requisites)
* [Notebooks](#notebooks)
* [References](#references)

## Important Note

This repository is for demo purposes only and runs a publicly available clothing transfer model, which does not include all improvements. Correspondingly, some functionality may be missing.
  
## Requisites

* [Conda](https://conda.io/docs/user-guide/install/index.html)
* [Octave 4.2+](https://www.gnu.org/software/octave/download.html) (with [image](https://octave.sourceforge.io/image/index.html) package)
  * Also compatible with MATLAB


### Test Example

To test whether the setup was successful, run the following command that should reproduce the clothing transfer shown at the top of the README:
```
./run_smartfit.sh inputs/example_person.jpg inputs/example_clothing.jpg
```
The corresponding output is `output/output.png` and should be similar to `output/example_output.png` (the right-most image above).

## References

This project builds from the work listed below:

* Human parsing
  * LIP_JPPNet ([repo](https://github.com/Engineering-Course/LIP_JPPNet), [paper](https://arxiv.org/abs/1804.01984))
* Pose estimation
  * Realtime Multi-Person Pose Estimation ([repo](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation), [paper](https://arxiv.org/abs/1611.08050))
    * [Keras implementation](https://github.com/michalfaber/keras_Realtime_Multi-Person_Pose_Estimation)
* Virtual try-on
  * VITON ([repo](https://github.com/xthan/VITON), [paper](https://arxiv.org/abs/1711.08447))
  
  * https://github.com/RohanBhandari/SmartFit
