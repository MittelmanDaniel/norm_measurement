# norm_measurement

Check out the notebook for code and the graphs

but takeaways:

Mean activation post centering: 101
Std of norms: 193.5480

However this is completely EXPLODED because the first token's activation is huge compared to the rest.

This happened with sample sizes from 1 all the way to 16 so I assume it was not random chance. 

When removing them the mean is close to 93-ish with significantly smaller variance.