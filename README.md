# Fourier transform and optics

`ft`: Fourier transform \
`go`: geometric optics \
`wo`: wave optics 

### Fourier transform

Main reference
* Lectures from Prof. Brad Osgood (Stanford)

`ft_01`
* Analysis and synthesis of period function
* Fourier series of function with period 1
* Inner product between functions
* Complex exponential as orthonormal basis for functions

`ft_02`
* Fourier series of function with period T
* Setup for Fourier transform as Fourier series with T goes to infinity
* Variables of Fourier and inverse Fourier transform

`ft_03`
* Shifting property
* Scaling property
* Derivative property
* Duality with reversed function

`ft_04`
* Convolution
* Convolution in one domain is multiplication in the other domain
* Convolution is commutative

`ft_05`
* Problem with classic Fourier transform definition
* Rapidly decreasing functions that work for classic definition
* Test function and distribution
* Delta function as distribution
* Ordinary function as distribution
* Fourier transform in context of distribution
* Some examples

`ft_06`
* Sampling property of delta function via multiplication
* Shifting property of delta function via convolution
* Scaling of delta function

`ft_07`
* Setup for Shah function
* Definition
* Poisson summation formula and Fourier transform of Shah function

`ft_08`
* Sampling theorem for bandlimited function
* Aliasing with undersampling
* Example of aliasing

`ft_09`
* Setup for discrete Fourier transform (DFT)
* Sampled form of function in time domain
* Continuous Fourier transform of sampled form of function
* Sampling in frequency domain to get sampled form of Fourier transform (of sampled form of function)
* Replace sampled forms with discrete functions
* Define DFT

`ft_10`
* Discrete complex exponentials
* Orthogonality between discrete complex exponentials
* Define inverse DFT
* Some examples of DFT
* Periodicity induced by discrete complex exponentials
* Duality for reversed function
* Shifting property in DFT

`ft_11`
* Discrete version of convolution
* Commutative and shifting property in convolution

`ft_12`
* Discrete version of delta function
* Multiplication and convolution with discrete delta function

`ft_13`
* Definition of linear system
* Sampling is a linear system
* Integration with kernel as infinite dimensional matrix multiplication
* Integration with kernel is the only form of continuous linear system
* Delta function and impulse response
* Impulse response of Fourier transform

`ft_14`
* Linear system in the case of convolution
* Delay operator
* Convolution with a delayed function is delay of (convolution with the function)
* Linear time-invariant system (LTI)
* Convolution is the only form of LTI system

`ft_15`
* Fourier transform of LTI system
* Complex exponentials are eigenfunctions of LTI system

`ft_16`
* Discrete LTI system with matrix-vector multiplication
* Complex exponentials are eigenvectors of discrete LTI system

`ft_17`
* 2D Fourier transform
* Spatial frequency

`ft_18`
* High dimensional Fourier transform of separable functions

`ft_19`
* Shifting property of high dimensional Fourier transform
* General scaling property of high dimensional Fourier transform
* Properties of high dimensional delta function

`ft_20`
* 2D Shah function and its Fourier transform

`ft_ex_01`
* Example: Fraunhofer diffraction
* Setup
* Far field approximation
* When nature is doing Fourier transform
* Far field diffraction pattern for common aperture functions

### Optics

Main reference 
* Lectures from Sander Konijnenberg (ASML)

`go_01`
* Convex and concave lens
* Real and virtual image

`go_02`
* Reflection
* Refraction and Snell's law

`go_03`
* Free space propagation
* Single thin lens propagation
* Paraxial approximation
* Transfer matrix
* Imaging condition

`go_04`
* Magnification factor
* Magnifier
* Microscope
* Telescope

`go_05`
* Chief ray and marginal ray
* Aperture
* Depth of focus

`wo_01`
* The concept of phase
* Wave equation
* Complex notation
* Plane wave

`wo_02`
* Refraction and Snell's law from plane wave equation
* Total internal reflection and Evanescent field

`wo_03`
* Spherical wave equation

`wo_04`
* Huygens–Fresnel principle

`wo_05`
* Double slit (point source) far field pattern
* As addition of complex-valued fields approximated as plane waves
* As path difference over integer multiple of wavelength

`wo_06`
* Diffraction grating with slits of negligible width (point source)
* Diffraction grating with slits of non-negligible width
* Grating spectroscopy
* Chromatic resolving power (resolvance)
* Free spectral range
* Numerical aperture (NA)

`wo_07`
* Michelson interferometry
* Tilted beam interference
* Haidinger pattern

`wo_08`
* Decompose initial field into plane waves with angular spectrum
* Propagate plane waves with plane wave equation
* Reconstruct field after propagation using angular spectrum

`wo_09`
* Huygens' principle
* Propagation of field using Rayleigh-Sommerfeld (R-S) integral
* R-S integral under Fresnel approximation
* R-S integral under Fraunhofer approximation
* Short notation for quadratic phase factor
* When is Fresnel approximation valid
* When is Fraunhofer approximation valid
* Fresnel number
