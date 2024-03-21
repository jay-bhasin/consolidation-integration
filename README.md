# Code for Bhasin et al., Synaptic weight dynamics underlying systems consolidation of a memory

Simulations are broken into six Jupyter notebooks, located in the `notebooks` directory of the repository:
- `simulations-heterosynaptic.ipynb`: consolidation in the feedforward circuit model with the heterosynaptic rule at the late-learning site (Figs. 2, S1), including perturbation of the early-learning site (Figs. 3, S2)
- `simulations-external-noise.ipynb`: simulations comparing the performance of a one- and a two-site model when the training signal is variable (Fig. 4)
- `simulations-hebbian.ipynb`: consolidation of the feedforward model with the Hebbian rule at the late-learning site (Fig. 5)
- `simulations-feedback-2d-inh-plasticity.ipynb`: consolidation in the model with a fixed-strength internal feedback loop using the inhibitory plasticity reset mechanism (Figs. 6A--E, S4A)
- `simulations-feedback-2d-instructive.ipynb`: consolidation in the model with a fixed-strength internal feedback loop using the inhibition of instructive signals reset mechanism (Figs 6F--J, S4B)
- `simulations-feedback-3d-instructive.ipynb`: consolidation in the model with plastic internal feedback loop using the inhibition of instructive signals reset mechanism (Fig. S3)

We also provide notebooks we used to check calculations of eigenvalues performed in the SI Appendix with symbolic methods: `calculations-heterosynaptic.ipynb` and `calculations-feedback-3d-instructive.ipynb` for the feedforward model with heterosynaptic plasticity rule, and the model with plastic feedback using the inhibition of instructive signals mechanism, respectively.
