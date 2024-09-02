# Neural-Encoding-and-Learning-in-Spiking-Neural-Networks
This project explores various encoding methods and unsupervised learning processes in spiking neural networks (SNNs) using Python.

It focuses on implementing different modes of neural information encoding, such as Time-to-First-Spike (TTFS), Rate Encoding, and Poisson Distribution Encoding. Additionally, the project delves into unsupervised learning with Spike-Timing-Dependent Plasticity (STDP) and the analysis of synaptic weight dynamics.

## Project Objectives
1. **Neural Encoding Schemes**: Implement and analyze different neural encoding methods to understand how information is represented in spiking neural networks.
2. **Unsupervised Learning with STDP**: Simulate and observe the effects of STDP on synaptic weight changes in a spiking neural network.
3. **Synaptic Plasticity**: Study the dynamics of synaptic weights and how they evolve through learning processes.
4. **Incorporation of Non-Spiking Neurons**: Investigate the impact of non-spiking neurons on the learning process and synaptic plasticity.

## Implemented Features
### 1. Neural Encoding Methods
- **Time-to-First-Spike (TTFS) Encoding**: Encodes information based on the time it takes for a neuron to generate its first spike.
- **Rate Encoding**: Encodes information by the firing rate of neurons over a specified time window.
- **Poisson Distribution Encoding**: Uses the Poisson distribution to generate spike trains based on firing rates.

### 2. Unsupervised Learning with STDP
- **Spike-Timing-Dependent Plasticity (STDP)**: Implements a learning rule where synaptic weights are adjusted based on the relative timing of pre- and post-synaptic spikes.
- **Synaptic Weight Dynamics**: Visualizes and analyzes the evolution of synaptic weights during the learning process.

### 3. Cosine Similarity for Neuronal Outputs
- **Cosine Similarity**: Measures the similarity between the firing patterns of output neurons to assess learning and pattern convergence.

### 4. Non-Spiking Neurons in SNNs
- **Incorporation of Non-Spiking Neurons**: Studies how the presence of non-spiking neurons influences synaptic plasticity and network behavior.

## Requirements
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `scipy`, `brian2`
