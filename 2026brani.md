Quantum Wavelet Shrinkage: From Qubits and Wavelet Scaling to Bayesian Attenuation Channels



Brani Vidakovic (Texas A\&M University)



Abstract: Wavelet shrinkage is a standard tool of nonparametric denoising and multiscale statistical inference. After an orthogonal wavelet transform, signal structure is often concentrated in a relatively small number of coefficients, while noise is spread across scales and locations. Classical methods exploit this separation by thresholding or smoothly attenuating empirical wavelet coefficients. The same statistical task becomes nontrivial in a quantum computational setting, because orthogonal wavelet transforms are naturally unitary, whereas shrinkage is nonlinear, dissipative, and generally noninvertible.



This talk develops a statistics-first route from classical wavelet shrinkage to quantum wavelet shrinkage. I begin with a short introduction to qubits, circuits, superposition, entanglement, measurement, and Qiskit-based simulation. I then explain why the Haar transform is closely connected to the Hadamard gate and how more general orthogonal wavelet transforms can be viewed as unitary operations on amplitude-encoded data. The discussion also includes nondecimated wavelet transforms, Hadamard-test energy estimation, and wavelet log-spectra for scaling and Hurst exponent analysis.



The main construction treats shrinkage as attenuation rather than as a forbidden nonlinear gate. In the Bayesian Adaptive Multiresolution Shrinkage framework, posterior means supply coefficientwise attenuation factors. These factors define a diagonal completely positive trace-preserving channel in the wavelet basis, with a minimal ancilla-based dilation. Conditioning on the retained ancilla branch reproduces the classical BAMS-shrunken coefficient vector up to the normalization inherent in amplitude encoding. The talk emphasizes what is mathematically exact, what is currently simulation based, and what remains open for hardware-aware quantum multiscale inference.

