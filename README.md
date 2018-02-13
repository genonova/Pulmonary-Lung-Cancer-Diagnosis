# Pulmonary Lung Cancer Diagnosis

Detection and Attention: Diagnosing Pulmonary Lung Cancer from CT by Imitating Physicians 

Abstract: This paper proposes a novel and efficient method to
build a Computer-Aided Diagnoses (CAD) system for lung nodule
detection based on Computed Tomography (CT). This task was
treated as an Object Detection on Video (VID) problem by
imitating how a radiologist reads CT scans. A lung nodule
detector was trained to automatically learn nodule features from
still images to detect lung nodule candidates with both high recall
and accuracy. Unlike previous work which used 3-dimensional
information around the nodule to reduce false positives, we
propose two simple but efficient methods, Multi-slice propagation
(MSP) and Motionless-guide suppression (MLGS), which analyze
sequence information of CT scans to reduce false negatives and
suppress false positives. We evaluated our method in open-source
LUNA16 dataset which contains 888 CT scans, and obtained
state-of-the-art result (Free-Response Receiver Operating
Characteristic score of 0.892) with detection speed (end to end
within 20 seconds per patient on a single NVidia GTX 1080) much
higher than existing methods. 

https://arxiv.org/ftp/arxiv/papers/1712/1712.05114.pdf

<b>Source code</b> and a <b>GUI lung cancer diagnosis platform</b> will be released.
