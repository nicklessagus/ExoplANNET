# ExoplANNET
A deep learning algorithm to detect and identify planetary signals in radial velocity data


The detection of exoplanets with the radial velocity method consists in detecting variations of the stellar velocity caused by an unseen
sub-stellar companion. Instrumental errors, irregular time sampling, and different noise sources originating in the intrinsic variability
of the star can hinder the interpretation of the data, and even lead to spurious detections.
In recent times, work began to emerge in the field of extrasolar planets that use Machine Learning algorithms, some with results that
exceed those obtained with the traditional techniques in the field. We seek to explore the scope of the neural networks in the radial
velocity method, in particular for exoplanet detection in the presence of correlated noise of stellar origin.
In this work, a neural network is proposed to replace the computation of the significance of the signal detected with the radial velocity
method and to classify it as of planetary origin or not. The algorithm is trained using synthetic data of systems with and without
planetary companions. We injected realistic correlated noise in the simulations, based on previous studies of the behaviour of stellar
activity. The performance of the network is compared to the traditional method based on null hypothesis significance testing.
The network achieves 28 % fewer false positives. The improvement is observed mainly in the detection of small-amplitude signals
associated with low-mass planets. In addition, its execution time is five orders of magnitude faster than the traditional method.
The superior performance exhibited by the algorithm has only been tested on simulated radial velocity data so far. Although in
principle it should be straightforward to adapt it for use in real time series, its performance has to be tested thoroughly. Future work
should permit evaluating its potential for adoption as a valuable tool for exoplanet detection
