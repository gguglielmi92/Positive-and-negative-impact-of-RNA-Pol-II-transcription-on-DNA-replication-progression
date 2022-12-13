# Positive and negative impact of RNA Pol II transcription on DNA replication progression

## Manuscript
Positive and negative impact of RNA Pol II transcription on DNA replication progression, manuscript submitted.. (https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3827411). 


## Description of the methods:


All the statistical tests were performed in R (4.0.3). Given samples A and B, the null and alternative hypotheses are respectively H_0: avg(d_A)!=avg(d_B) and  H_1:avg(d_A )≠avg(d_B ), where avg(d_X ) denotes the sample mean of the Boolean vector I[d_X==0], while d_X is the BrdU peaks/breakpoint in sample X. Consequently, the statistics is defined as t^*= avg(d_A )-avg(d_B ). To relax the distributional assumptions, statistical tests were performed by employing the bootstrap permutation procedure with at least 10,000 times of resampling for each test. Once p-values are computed, Benjamini–Yekutieli (BY) correction was applied in order to mitigate the Type I error and consider any potential correlation across the multiple tests.
