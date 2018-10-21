# Kaggle_TGS

Code for my best model in the Kaggle TGS competition: https://www.kaggle.com/c/tgs-salt-identification-challenge

This model scores 0.871 on the private LB score. From a deep learning architecture point of view it is not advanced by any mean, I am sharing it just because some competitors wanted to see it!  The only value is that I achieved a Silver medal with this while having spent only 10 days in that competition.

There may be some bits of interest, described in my write up: https://www.kaggle.com/c/tgs-salt-identification-challenge/discussion/69052

I only share the best model here.  The full solution had 3 other, weaker models, using my won encoder/decoder architecture.  The only part that was changed was the build_model() function.  Averaging their predictions would yield 0.874 on the private LB.  I did a bit better with ensembling, getting to 0.875, see the write up.
