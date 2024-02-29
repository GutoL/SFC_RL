# Reinforcement Learning for Service Function Chain (SFC) Placement
<!--
This repository contains the notebook which has a solution using reinforcement learning (RL) for SFC placement. A simulator was developed using python to simulate the arrival of SFC requests and eventual failures/repair events of the infrastructure components. The environment was developed using the openAI gym framework. The library stable baselines was used to develp the RL agents.
-->

This repository hosts a comprehensive solution employing reinforcement learning (RL) techniques for optimizing Service Function Chain (SFC) placement in dynamic network environments. 

## Features:

- **Reinforcement Learning Solution**: The repository contains Jupyter notebooks presenting a robust RL solution tailored for SFC placement optimization. RL algorithms are utilized to dynamically adapt SFC configurations based on changing network conditions and demands.

- **Python Simulator Development**: A Python-based simulator has been meticulously crafted to emulate the arrival of SFC requests and to simulate potential failures or repair events within the underlying infrastructure. This simulator serves as a crucial tool for testing and validating the RL-based placement strategies.

- **OpenAI Gym Environment**: Leveraging the flexibility and extensibility of the OpenAI Gym framework, an adaptable environment has been constructed to facilitate RL experimentation and training for SFC placement scenarios.

- **Stable Baselines Library Integration**: The solution harnesses the capabilities of the Stable Baselines library, a powerful toolkit for RL model development and training. By integrating Stable Baselines, developers can efficiently design and optimize RL agents for SFC placement tasks.

## Key Components:

- **Notebook**: The notebook within this repository serves as a comprehensive guide, detailing the implementation and evaluation of the RL-based SFC placement solution. It provides insights into the underlying algorithms, simulation methodologies, and experimental results.

- **Simulator Codebase**: The Python codebase encapsulating the SFC request arrival simulation and infrastructure event modeling is included, offering a flexible and customizable framework for scenario-based testing and analysis.

- **RL Agent Implementations**: Various RL agents tailored for SFC placement optimization are developed using Stable Baselines. These agents are trained and evaluated within the provided environment to ascertain their effectiveness in real-world deployment scenarios.

<!--
By combining cutting-edge RL methodologies with realistic simulation environments, this repository offers a practical framework for addressing SFC placement challenges in dynamic network landscapes. Developers and researchers alike can leverage the provided resources to explore, experiment, and innovate in the realm of network optimization and automation.
-->

# Cite our work
If you use this project in your work, please consider citing our article:

```BibTeX
@article{santos2021availability,
  title={Availability-aware and energy-aware dynamic SFC placement using reinforcement learning},
  author={Santos, Guto Leoni and Lynn, Theo and Kelner, Judith and Endo, Patricia Takako},
  journal={The Journal of Supercomputing},
  pages={1--30},
  year={2021},
  publisher={Springer}
}
```
```txt
Santos, G. L., Lynn, T., Kelner, J., & Endo, P. T. (2021). Availability-aware and energy-aware dynamic SFC placement using reinforcement learning. The Journal of Supercomputing, 1-30.
```
