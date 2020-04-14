# Connectivity analysis in MEG and EEG data

- https://www.youtube.com/watch?v=ZBwh0Vm4fh4
- Univariate analysis:
  - time course of activation => processing steps (ERP, averaging, TF, source analysis)
  - each channel reflects activity of sources close to sensor
- Beyond univariate: connectivity
  - combine measurements recorded at >1 locaiton
- Measures of connectivity:
  - Effective (causal) vs functional (statistical)
  - Model-based (e.g. DCM) vs data-driven
  - Time vs frequency domain
  - Linear vs non-linear
- Frequency domain connectivity
  - many measures, focused around phase synchrony
- Oscillations:
  - signal with changing amplitude as a function of time (periodic)
  - period - distance between two peaks
  - amplitude - distance from 0
  - phase
  - ![image-20191223151916604](/Users/nika/Library/Application Support/typora-user-images/image-20191223151916604.png)
  - phase defines where you are within 1 cycle
- oscillations can be represented in polar coordinates
- $S = Ae^{i\phi}$
  - A - amplitude
  - $\phi$ - phase angle
  - simplifies mathematical operations
- Observing and comparing several oscillations
  - phase difference moves around - low synchrony
  - phase difference constant or clustered - high synchrony
-  $x_1=A_1e^{i\phi_1}$ - signal 1
- $x_2=A_2e^{i\phi_2}$ - signal 2
-  $x_1x_2*=\langle A_1A_2e^{i(\phi_1-\phi_2)}\rangle$
  - multiplying signal 1 by signal 2 with a flipped sign of the phase
- => CSD = fourier transform of S1 * conj(S2) => complex valued number that represents a signal in which the amplitude is the product of A1 and A2 and the phase is the phase difference
- Coherence
  - Computed from the cross-spectral density![image-20191223160136032](/Users/nika/Library/Application Support/typora-user-images/image-20191223160136032.png)
  - each circle is the single trial cross-spectral density
  - (put the arrows head to tail (sum) and normalize)
- ![image-20191223160334717](/Users/nika/Library/Application Support/typora-user-images/image-20191223160334717.png)

- 1/N - normalize by averaging
- denominator - normalization term - sqrt of the product of average amplitudes
  - similar to Pearson’s correlation coefficient: covariance (element wise product across measurements) / product of the variance
- coherence is equivalent to the frequency domain representation of the cross-correlation coefficient
- PLV: same but without the amplitude
- coherency - same as coherence but w/o the absolute 
  - 