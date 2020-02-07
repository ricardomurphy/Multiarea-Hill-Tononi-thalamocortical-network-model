# Multiarea-Hill-Tononi-thalamocortical-network-model

The cellular and network mechanisms underlying brain states and conditions permitting or suppressing conscious experience remain elusive. Computational models of neuronal networks can help interpret experiments and generate testable predictions. With these considerations in mind, we have implemented in the neural simulator NEST a ‘toy brain’ comprising left and right hemispheres, each with three cortical areas and associated thalamic nuclei. Each neuronal layer comprises hybrid conductance-based/integrate-and-fire neurons based on [1]. Intrahemispheric connectivities are based on [2], with modifications to synaptic weights to enhance the propagation of the response to trans-cranial magnetic (TMS) stimulation. Interhemispheric connectivities are based on [3]-[6]. For comparison with ECoG and EEG data, the principal output of the model is the local field potential (LFP) estimated as a weighted sum of synaptic current magnitudes [7]. The implementation allows modification of network parameters via text files or python functions. Parameters for simulated wake and sleep are provided.
