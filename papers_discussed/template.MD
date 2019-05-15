### Title

Focal Loss for Dense Object Detection

### tl;dr

The paper first investigates why one-stage object detection networks trail in accuracy compared to two-stage models and then proposes a new loss function to improve upon the shortcomings.

### Describe the method

The paper identifies the biggest issue with one-stage detector as the high class imbalance of foreground and background objects that one-stage detectors have to face. The number of pixels corresponding to background far outnumber the number of pixels corresponding to the number of pixels for the foreground.

To fix the imbalance, the authors propose a new loss function based on categorical cross-entropy with a scaling factor to 

### Any further details

> Further references

### My two cents

> Anything constructive you make from the paper or which 'tweak of architecture" do you propose or a transfer learning solution or anythin' weird
