**Overview**
Diabetic retinopathy is an ophthalmological condition affecting individuals with diabetes, leading to distress in the retina due to the development of blood clots, lesions, or hemorrhages. This condition is characterized by the proliferation of optical nerves and the formation of mesh-like structures in the retinal vasculature.

**Purpose**
The purpose of this project is to develop a Convolutional Neural Network (CNN) for the classification of diabetic retinopathy using fundus scans of the eye. Prior to segmentation, pre-processing techniques are applied to enhance the quality of the images.

**Pre-processing**
Fundus scans undergo pre-processing using the maximal primary curvature approach, utilizing the maximum Eigenvalues of the Hessian matrix to extract branching blood veins.
Morphological opening and adaptive histogram equalization are applied to refine and eliminate incorrectly segmented areas.

**CNN Architecture**
The classification model employs a CNN architecture with convolutional and pooling layers for distinguishing between diabetic and healthy retinas.

**Dataset**
The model is trained and evaluated using the DIARETDBI dataset.

**Results**
The CNN is expected to provide accurate classification between diabetic retinopathy and healthy retinas, aiding ophthalmologists in diagnosis.
