# COMP591 Research Paper: Analysing Branch Prediction using OpenPAT

This research paper investigated using the OpenPAT project to measure the performance of various branch predictors for pipelined CPUs. It also investigated replacing one or two bits within a JUMP instruction to hint which one of alternate available branch predictors should be used at a given instruction. This 'tagged' branch predictor was shown to be more accurate than any of the investigated branch predictors, especially at smaller predictor cache sizes.

Overall, the tagged branch predictor was shown to out-perform much larger predictors, with no predictor tested able to outperform a TBP with 8KB of cache. And the TBP often used half or a quarter of the chip space of comparably performant predictors. The conclusion was made that no single large predictor would be able to out-perform a small tagged branch predictor, for the given test suite.

This research was originally done in 2014, and subject to a 12-month NDA. Somehow an extra pair of 00's made it onto the NDA form, transforming it to 100 years. Which seems wholly unreasonable for an under-graduate paper.
