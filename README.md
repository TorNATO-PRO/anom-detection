# Anomaly Detection using Matrix Profiling on Cybersecurity Datasets

The idea behind this project is to use Matrix Profiling and compare its anomaly detection performance with various machine learning algorithms on a cybersecurity dataset. To get started, I highly recommend checking out the following links:

- [The Matrix Profile Foundation](https://matrixprofile.org/) Provides utilities for computing Matrix Profiles.
- [This presentation](https://www.cs.ucr.edu/~eamonn/Matrix_Profile_Tutorial_Part2.pdf) provides information about Matrix Profiling.
- [This repository](https://datascience.aeolus.wsu.edu/nwaltz/cyber-security-analysis) has information related to the paper that I wrote.

So that should give you a good enough synopsis about what Matrix Profiling is and how it is used. Now, we will segue into talking about the [paper that I wrote](https://www.overleaf.com/read/txttqnhtdnrp). Basically, we used the UNSW-NB15 [^UNSW] dataset to train machine learning algorithms to detect and classify attacks, and we got pretty good results - although if you looks at our confusion matrixes and analyses you can see why those results are misleading. I think a good project for you would be to do something similar on a cybersecurity time-series dataset with fixed time windows that James will provide. So, be sure to read up about Matrix Profiling and **communicate** with me or James if you have any issues.

Here is the abstract of the paper if that helps pique your interest:

> Cybersecurity is a field of great interest that affects every person, and every
> agency that uses networks is at risk of falling victim to a network attack. According
> to IBM, 52% of data breaches are the result of malicious attacks, and an average
> data breach and costs a business $3.86 million and takes around 280 days to detect
> and contain [4]. It is therefore imperative that functional attack detectors exist
> and are available to counter this threat. There is a plethora of network traffic
> datasets available for analysis, but many network traffic datasets tend to be very
> large and unlabeled. This limits the ability of people to train supervised machine
> learning models to perform attack detection and classification tasks. However,
> labeled datasets like the UNSW-NB15 dataset [19] do exist and are indispensable
> for training machine learning models to perform cyberattack detection. Using this
> dataset, we have achieved 99% accuracy classifying whether a given observation
> in the UNSW-NB15 dataset is an attack, and around 89% accuracy in classifying
> the type of the attack. We have also compared the efficacy of different supervised
> machine learning models on this dataset and found matrix profiling to be ineffective
> on this dataset for the attack detection problem.


[^UNSW]: [The UNSW-NB15 Dataset | UNSW Research](https://research.unsw.edu.au/projects/unsw-nb15-dataset) - A dataset that contains various network traffic that was created using normal activities as well as synthetic attack methods.
