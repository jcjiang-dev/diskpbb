# diskpbb
A fast compiled Xspec table model for multi-temperature disk blackbody emission

An Xspec table model for a multi-temperature black body disk. The index of the temperature profile (p) is a free parameter. This model is the same as the original additive Diskpbb model in Xspec (Kubota et al. 1998), but much faster.

kTin: The temperature of the inner radius of the disk in keV
p: The exponent of the radial dependence of the disk temperature
k: log((Rin/D)^2*cos(theta)), where where Rin is the apparent inner disk radius in km, D the distance to the source in units of 10 kpc, and theta is the angle of the disk ($\theta = 0$ is face-on). On the correction factor between the apparent inner disk radius and the realistic radius, see e.g., Kubota et al. (1998). This parameter is the equivalent of the normalisation parameter in the original Diskpbb model in Xspec but in log.
Redshift: the redshift of your target
norm: This parameter needs to fixed at 0.0161183.
