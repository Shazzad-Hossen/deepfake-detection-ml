
The rapid advancement of deepfake technologies has emerged
as a critical threat to the authenticity of digital media through the cre-
ation of highly realistic but fake visual content. The use of advanced video
manipulation tools undermines public trust, poses security risks and chal-
lenges the integrity of information across digital platforms. Although sig-
nificant progress has been made in deepfake image detection, research on
identifying advanced video manipulations, particularly in low-resolution
videos remains limited. To address this gap, we propose a deepfake video
detection framework by using transfer learning approach. Initially, our
method analyzes each extracted frame using a CNN-based architecture
to generate frame-level predictions, which are then aggregated by aver-
aging. Based on a predefined threshold, the framework finally classifies
the video as real or manipulated. For experimentation, we utilized a
publicly available dataset named “FaceForensics++” containing a total
of 2,000 real and manipulated videos of varying quality and resolution.
We explored various CNN architectures and vision transformer models,
including Xception, Inception, DenseNet, and ViT-Large, along with rig-
orous hyperparameter tuning. Among these, the Xception architecture
outperformed others by achieving a test accuracy of 94.5%. This research
offers an effective solution to the growing challenge of deepfake detection
that facilitates the development of robust and scalable tools that are
vital for preserving information integrity in the industry 4.0.
