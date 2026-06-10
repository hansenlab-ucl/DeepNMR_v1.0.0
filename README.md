<h1 align="center">DeepNMR</h1>

<img width="1280" height="673" alt="DeepNMR" src="https://github.com/user-attachments/assets/e6aac31a-9acf-4f4a-8f6f-3af25fb91ff0" />


##
DeepNMR is distributed under the MIT License and includes the required TopSpin macros, example datasets, pulse sequences, parameter files, installers for all supported operating systems, and a comprehensive user manual. 

##
Download link: https://www.dropbox.com/scl/fo/3oea4bf3j8p3w0ykzu0ja/ADvCB3Gwj7czXdTbdtFvYWc?rlkey=77gy9pwnqss1czud1xhcv3cgz&st=s89rnojp&dl=0

# DeepNMR v1.0.0 (Alpha Release)

DeepNMR allows one to run deep neural networks directly on the NMR spectrometer, with a simple installation and fully integrated TopSpin workflows. The module is available for TopSpin 3.x, 4.x, and 5.x on macOS, Linux, and Windows 11.

This first release includes three deep learning models:

# FIDNETPS
Deep learning-assisted pure shift NMR for small molecules, generating high-resolution virtually homonuclear decoupled spectra from spin-echo modulated data. The module supports both 1D and 2D pure shift applications.

# Single13CH
Reconstruction of methyl 1H-13C correlation maps from single-pulse off-resonance decoupling experiments recorded on large proteins labelled with 13CHD2 methyl groups.

# Aromatic FIDNet2
Virtual 13C-13C homodecoupling and resolution enhancement of aromatic side-chain 2D ¹H-¹³C HSQC spectra, enabling improved characterisation of aromatic residues in proteins.

##
We hope DeepNMR will make deep learning-enhanced NMR processing more accessible to the community and help users process spectra directly at the spectrometer. Please let us know of any questions or suggestions you may have.

### References:

1. V. M. R. Kakita, D. F. Hansen, J. Am.Chem. Soc. 2026, 148, 9, 9226–9230. Deep Learning‑Assisted Proton Pure‑Shift NMR Spectroscopy. https://doi.org/10.1021/jacs.5c22860

2. N. P. Khandave, V. M. R. Kakita, C. J. Buchanan, V. K. Shukla, K. Haubrich, P. Vallurupalli, D. F. Hansen,  Proc. Natl. Acad. Sci. USA, 2026, 23, 17, e2527937123. Two-dimensional NMR from a single pulse: Reconstructing heteronuclear 2D spectra via off-resonance decoupling and deep neural networks https://doi.org/10.1073/pnas.2527937123

3. V. K. Shukla, G. Karunanithy, P. Vallurupalli, D. F. Hansen,  Sci. Adv. 2024, 10, eadr2155. A combined NMR and deep neural network approach for enhancing the spectral resolution of aromatic side chains in proteins https://doi.org/10.1126/sciadv.adr215
