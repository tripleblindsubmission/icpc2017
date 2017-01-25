## ICPC'17 Blind Submission
Repository to harbour experiment material
------------------------------------------------
# Variability through the Eyes of the Programmer

### Abstract.
Many software projects rely on preprocessors (#ifdefs) to implement compile-time variability. At the same time, many researchers and practitioners criticize preprocessor for increasing complexity, hampering maintainability and comprehensibility of code. Existing studies show that bug finding in presence of variability is time-consuming; developer’s efficiency during debugging decreases linearly with the degree of variability. However, little is known about the cognitive process of debugging the programs with preprocessor variability. We carry out an experiment to qualitatively understand how developers approach and debug programs with variability. We ask developers to debug programs with and without variability, and we record their eye movements using an eye-tracking device, while they are debugging.

The results indicate that variability increases debugging time of code fragments that contain variability. Interestingly, debugging time also seems to increase for code fragments without variability in the proximity of fragments that do contain variability. In addition, we find that variability makes the number of gaze transitions (eye switches) grow between definition-usages for fields and call-returns for methods. We also notice that most developers initiate debugging with an “initial scan” of the program from the first line down to the last, independent of variability. However, variability seems to prolong this “initial scan” of the program. Finally, we observe that developers appear to debug programs with variability by considering either one configuration at a time (consecutively) or all configurations at the same time (simultaneously).

These findings shall inspire designers of debugging and visualization tools for variability, and contribute to more effective debugging.
