# Face Bounding Box Detection with Haar Cascade

This repository contains a collection of Haar cascade XML files for face detection and an example Python script for utilizing these XML files to detect and draw bounding boxes around faces in images or video streams.

## Haar Cascade XML Files

The Haar cascade XML files are trained models used for object detection, specifically for detecting faces in this case. These XML files define a set of features and rules that are used to classify regions of an image as either containing a face or not. The repository includes pre-trained Haar cascade XML files that can be used out of the box.

The following Haar cascade XML files are included:

- `haarcascade_face.xml`: The default Haar cascade XML file for frontal face detection.
- `haarcascade_eyes.xml`: The default Haar cascade XML file for eyes detection.
- `haarcascade_mouth.xml`: The default Haar cascade XML file for mouth detection.
  
Feel free to experiment with other XML files to see which one performs best for your specific use case.
