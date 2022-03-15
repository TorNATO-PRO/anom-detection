# Anomaly Detection using Matrix Profiling on Cybersecurity Datasets

The idea behind this project is to use Matrix Profiling and compare its anomaly detection performance with various machine learning algorithms on a cybersecurity dataset. To get started, I highly recommend checking out the following links:

- [The Matrix Profile Foundation](https://matrixprofile.org/) Provides utilities for computing Matrix Profiles.
- [This presentation](https://www.cs.ucr.edu/~eamonn/Matrix_Profile_Tutorial_Part2.pdf) provides information about Matrix Profiling.
- [This repository](https://datascience.aeolus.wsu.edu/nwaltz/cyber-security-analysis) has information related to the paper that I wrote.

So that should give you a good enough synopsis about what Matrix Profiling is and how it is used. Now, we will segue into talking about the [paper that I wrote](https://www.overleaf.com/read/txttqnhtdnrp). Basically, we used the UNSW-NB15 [^UNSW] dataset to train machine learning algorithms to detect and classify attacks, and we got pretty good results - although if you looks at our confusion matrixes and analyses you can see why those results are misleading. I think a good project for you would be to do something similar on a cybersecurity time-series dataset with fixed time windows that James will provide. So, be sure to read up about Matrix Profiling and communicate with us if you have any issues.


[^UNSW]: [The UNSW-NB15 Dataset | UNSW Research](https://research.unsw.edu.au/projects/unsw-nb15-dataset) - A dataset that contains various network traffic that was created using normal activities as well as synthetic attack methods.
