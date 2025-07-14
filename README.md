This project explores the application of Dynamical Components Analysis (DCA) to various downsampled animated movie clips. The goal is to identify spatial patterns (pixel groups) that best predict future frames. DCA is compared with PCA on two of the clips (`projectiles.mp4` and `flare.mp4`) to evaluate its ability to extract meaningful dynamic representations in time-series data like video.

**Key finding:** Unlike PCA, DCA successfully isolates the moving alien spaceship and flare activity, which are predictive of the next frames in the video.

Inspired by ongoing work in the Dr. Bouchard's Neural Systems and Machine Learning Lab (NSML) at the Lawrence Berkeley National Laboratory, which developed Dynamical Components Analysis (DCA) as a method to find population-level dynamical structure in neuroscience data.

Sources:
- github: https://github.com/BouchardLab/DynamicalComponentsAnalysis
- Unsupervised Discovery of Temporal Structure in Noisy Data with Dynamical Components Analysis. Livezey, J, Clark, D.G., Bouchard, K.E.; NeurIPS 2019.
- Predictibility, complexity, and learning. William Bialek, Ilya Nemenman, and Naftali Tishby; _Neural Computation_, 13(11):2409–2463, 2001.


