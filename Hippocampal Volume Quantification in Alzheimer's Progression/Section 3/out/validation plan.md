# Validation Plan

## How is ground truth defined?
The silver standard of radiologist reading.

## How is accuracy of the algorithm defined?
Jaccard and Dice similarity to the ground truth.

**Ground Truth Acquisition Methodology:**

The golden standard for obtaining ground truth would be to perform 
one the tests.

Yet, tests are quite expensive, and in most cases diagnosis is 
concluded by the physician based on radiologist's analysis/description.
Since the purpose of this device is assisting the radiologist (not replacing him),
the ground truth for the FDA Validation Dataset can be obtained as an average 
of three practicing radiologists (as a widely used 'silver standard').
The same method is used in the mentioned paper.  


## What data can the algorithm operate on?
MRI scans on hippocampus stored in the DICOM format.


