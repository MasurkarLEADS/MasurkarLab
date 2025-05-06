After loading NEURON, paste "paste this code"

Superficial cell models are:
6-5 s3c3
6-13 s3c3
6-24 s1c1
81915

Deep cell model are:
11-19 s1c1
11-12 s3c5
6-24 s2c2
6-5 s4c4

To remove spines by X% in SR or SLM, multiply factorSR or factorSLM, respectively, by X/100.

The .mod files include the 2 calcium channels and 1 calcium-sensitive potassium channel to be included in the distal dendrite for plateau potential generation. The model otherwise uses default NEURON fast sodium and delayed rectified potassium current.
