# Image-Super-Resolution

## Introduction

Super-resolution imaging (SR) is a class of techniques that enhance the resolution of an imaging system. In some SR techniques—termed optical SR—the diffraction limit of systems is transcended, while in others—geometrical SR—the resolution of digital imaging sensors is enhanced.

In some radar and sonar imaging applications (e.g., magnetic resonance imaging (MRI), high-resolution computed tomography), subspace decomposition-based methods (e.g., MUSIC[1]) and compressed sensing-based algorithms (e.g., SAMV[2]) are employed to achieve SR over standard periodogram algorithm.

Super-resolution imaging techniques are used in general image processing and in super-resolution microscopy.


## Basic concepts

Because some of the ideas surrounding super-resolution raise fundamental issues, there is need at the outset to examine the relevant physical and information-theoretical principles.

Diffraction Limit The detail of a physical object that an optical instrument can reproduce in an image has limits that are mandated by laws of physics, whether formulated by the diffraction equations in the wave theory of light[3] or the Uncertainty Principle for photons in quantum mechanics.[4] Information transfer can never be increased beyond this boundary, but packets outside the limits can be cleverly swapped for (or multiplexed with) some inside it.[5] One does not so much “break” as “run around” the diffraction limit. New procedures probing electro-magnetic disturbances at the molecular level (in the so-called near field)[6] remain fully consistent with Maxwell's equations.

A succinct expression of the diffraction limit is given in the spatial-frequency domain. In Fourier optics light distributions are expressed as superpositions of a series of grating light patterns in a range of fringe widths, technically spatial frequencies. It is generally taught that diffraction theory stipulates an upper limit, the cut-off spatial-frequency, beyond which pattern elements fail to be transferred into the optical image, i.e., are not resolved. But in fact what is set by diffraction theory is the width of the passband, not a fixed upper limit. No laws of physics are broken when a spatial frequency band beyond the cut-off spatial frequency is swapped for one inside it: this has long been implemented in dark-field microscopy. Nor are information-theoretical rules broken when superimposing several bands,[7][8] disentangling them in the received image needs assumptions of object invariance during multiple exposures, i.e., the substitution of one kind of uncertainty for another.

Information When the term super-resolution is used in techniques of inferring object details from statistical treatment of the image within standard resolution limits, for example, averaging multiple exposures, it involves an exchange of one kind of information (extracting signal from noise) for another (the assumption that the target has remained invariant).

Resolution and localization True resolution involves the distinction of whether a target, e.g. a star or a spectral line, is single or double, ordinarily requiring separable peaks in the image. When a target is known to be single, its location can be determined with higher precision than the image width by finding the centroid (center of gravity) of its image light distribution. The word ultra-resolution had been proposed for this process[9] but it did not catch on, and the high-precision localization procedure is typically referred to as super-resolution.

In summary: The technical achievements of enhancing the performance of imaging-forming and –sensing devices now classified as super-resolution utilize to the fullest but always stay within the bounds imposed by the laws of physics and information theory.
