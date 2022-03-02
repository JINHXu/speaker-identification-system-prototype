## Speaker Identification (98% identification accuracy)

How to build a __high-performance \& low-cost__ industrial (data-driven) speaker identification system with 98% identification accuracy using the state-of-the-art algorithms implemented with open-source packages and frameworks? This thesis describes an extensive research conducted towards the goal of building such a system prototype. The research answers the following questions:

- what are the state-of-the-art algorithms? NN-based `SpeakerNet` vs. classic ML `MFCC-GMM`
- how does the model performance change over different amount of training data (closed-set vs. open-set)
- how does the model performance change over different amount of inference data (closed-set vs. open-set)
- in an open-set identification enviroment, instead of setting a confidence threshold, how does using a class of various speaker recordings to represent an un-enrolled work?


### prototype system specifics

- minimum required training data per user: 3 min
- minimum required data for each inference on the run: 3 seconds
- system: ROS (Robot Operating System)


### Abstract

> Speaker identification has numerous applications in various areas. Over the years, there has been a rising need for automated speaker identification systems in the industry. This thesis explores __text-independent__ speaker identification on short audio samples using __data-driven__ methods. In particular, it concentrates on the available solutions with high identification accuracy and seeks to build a high-performance practical system. The experiments compare two of the state- of-the-art statistical models for the task, examine the effect of the amount of training data on model performance in closed-set and open-set settings, and ex- amine the effect of marginal change on inference audio length on identification accuracy. The highest accuracy achieved by both models in the experiments surpass __0.985 in a closed-set setting__, and __0.978 in an open-set setting__. Beyond discussing the observations and findings from the experiments, this thesis describes the practical speaker identification systems built in the process based on the experiment results and provides a reproducible pipeline for building a high-performance practical speaker identification system.

- View the [Thesis](https://drive.google.com/file/d/1wwnwZCggz4F4Jgulazgf30MfqzDbgCSN/view?usp=sharing)


### Links

* [Tutorial: speaker identification using SpeakerNet](https://github.com/JINHXu/tutorial-speaker-identification-with-nemo)

* [Convert Large MD tables to Latex (automatic parser)](https://github.com/JINHXu/MDtable2Latex)

_This thesis received a grade of 1.0/1.0 (German scale) at the University of Tübingen._
