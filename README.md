# norm_measurement

Check out the notebook for code but takeaways.

Mean activation post centering: 101
Std of norms: 193.5480

However this is completely EXPLODED because the first token's activation is huge compared to the rest.

This happened with batch sizes from 1 all the way to 16. When removing them the mean is close to 93-ish with significantly smaller variance.