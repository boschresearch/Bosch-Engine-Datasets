# Datasets
We provide two datasets _gengine1_ and _gengine2_.
Each dataset consists of _N_ measurements of the gasoline engine
D = {d<sub>1</sub>,...,d<sub>N</sub>}. Each measurement d = {(u<sub>1</sub>, y<sub>1</sub>),...,(u<sub>T</sub>, y<sub>T</sub>)} contains a trajectory
of length _T_ where the inputs are denoted as
u<sub>t</sub> and the outputs as y<sub>t</sub>.
The length of the trajectory may vary between measurements.
The data points are recorded every _10 Hz_.
Each measurement is saved as a separate csv-file.
The data is standardized to mean-zero and unit-variance on the training data set.

## Dataset 1
The dataset _gengine1_ contains in total _66_ measurements.
We used the measurements _[10,11,12,13,14,15,16,17,18,19,30,31,32,33,34,35,36,37,38,39]_
for training and the measurements _[53,54,55,56,57,58,59,60,61,62,63,64,65]_ for
testing.

The first 5 columns correspond to the inputs u<sub>t</sub>:

- Speed
- Load
- Lambda
- Ignition Angle
- Fuel Cutoff

The last 8 columns correspond to the outputs y<sub>t</sub>:

- Particle Numbers
- HC
- CO
- CO2
- Nox
- O2
- Temperatue (Exhaus Manifold)
- Temperate (Catalyst 1)

## Dataset 2
The dataset _gengine2_ contains in total _22_ measurements.
We used the measurements _[0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]_
for training and the measurements _[16,17,18,19,20,21]_ for
testing.

The first 4 columns correspond to the inputs u<sub>t</sub>:

- Speed
- Load
- Lambda
- Ignition Angle

The last 5 columns correspond to the outputs y<sub>t</sub>:

- Particle Numbers
- HC
- Nox
- Temperatue (Exhaus Manifold)
- Temperature (Catalyst 1)
