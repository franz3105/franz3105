# Francesco Preti

**Machine Learning · Quantum Computing and Control · Scientific Software**

I'm a physicist and scientific software developer based in Aachen, Germany. 

My work combines reinforcement learning, agentic AI, quantum control, optimization, and
GPU-accelerated numerical simulation. I also recently worked on Bayesian Optimization, LLM fine-tuning and distributed ML.

I hold a PhD in Physics from the University of Cologne and currently work as an AI Consultant at the Jülich
Supercomputing Centre, as a member of Helmholtz AI: [SDL Applied Machine Learning](https://www.fz-juelich.de/en/jsc/about-us/structure/simulation-and-data-labs/sdl-applied-machine-learning).

I develop Python and JAX software for quantum-device dynamics and scalable
computational experiments. My engineering experience includes pytest, Git,
CI pipelines on the JSC cluster (JUBE).

[GitHub](https://github.com/franz3105) ·
[LinkedIn](https://www.linkedin.com/in/francesco-preti/) ·
[ORCID](https://orcid.org/0000-0003-3819-3445) ·
[Email](mailto:f.preti@protonmail.com)

## Selected work

### Reinforcement learning for trapped-ion circuit compilation

Public research code accompanying *Hybrid discrete-continuous compilation of
trapped-ion quantum circuits with deep reinforcement learning*.

- **Problem:** Hybrid discrete-continuous quantum circuit compilation.
- **My contribution:** I developed the entire framework (the RL PyTorch implementation and the quantum circuit simulation in JAX and Numba) and its integration on HPC systems.
- **Approach:** The RL algorithm optimizes unitary synthesis and state preparation with respect to discrete-continuous parameters in trapped-ion circuits.
- **Results:** The agent is effective in guiding the continuous optimization algorithm towards optimal solutions in the discrete-continuous optimization landscape: [Publication](https://quantum-journal.org/papers/q-2024-05-14-1343/#)
- **Engineering:** The code integrates both Numba and JAX with my own and other reinforcement learning algorithms. It also includes tests and standard quantum compilation approaches.

[Source code](https://github.com/franz3105/RL_Ion_gates), [data](https://zenodo.org/record/8288977)

## Ongoing projects (FZJ Gitlab)

Some current work is not publicly available or will be available on the GitLab pages of FZJ.

### Multi-agent reinforcement-learing for power-grid control

Developing a reinforcement-learning codebase for power-grid control using
pandapower, including automated testing and CI pipelines.

- **My contribution:** We are studying multi-agent reinforcement learning (MARL) systems for a pandapower environment that -- in its upcoming version -- will also model the power grid of the Forschungszentrum Jülich.
- **Status:** In development. Ray code is currently running on the JSC Cluster.
- **Code availability:** At the moment, the code is not publicly available.
- **Engineering**: This repo integrates [Ray + RLlib](https://docs.ray.io/en/latest/index.html) with SLURM and uses [pandapower](https://www.pandapower.org/) .

- ### Agentic AI for [ParaQeet](https://paraqeet.readthedocs.io/en/latest/)

Developing an agentic AI system for integration into the quantum control
library ParaQeet. A working prototype currently runs on an HPC cluster.

- **Status:** Prototype development; library integration ongoing.

### Quantum compilers and partitioners

Developing a quantum compiler project to explore modular transformation
workflows, correctness, and benchmark-driven evaluation.

- **My contribution:** I am co-developing both the repo and the algorithmic implementation.
- **Validation:** We are currently benchmarking the decompositions against known methods.
- **Status:** In development. Some preliminary results in: https://arxiv.org/abs/2606.04070v1.


## Technical skills

| Area | Tools and methods |
| --- | --- |
| Programming | Python, Julia, Bash |
| Scientific computing | JAX, NumPy, differentiable simulation |
| Machine learning | PyTorch, Hugging Face, reinforcement learning (RLlib), Bayesian optimization |
| Quantum computing | Quantum control, Quantum optimization, Qiskit, PennyLane |
| Testing and development | pytest, automated testing, Git, CI pipelines |
| Computational infrastructure | Ray, SLURM, distributed workflows, GPU computing |

## Research background

My PhD thesis, *Optimal Control and Machine Learning of Quantum Device
Dynamics*, focused on reinforcement learning, quantum control, and quantum
optimization. I have also supervised Master's students and presented my work
to international technical audiences.

Selected publications include work in *PRX Quantum* (2022), *Quantum* (2024),
and *Physical Review Research* (2024). See my
[ORCID profile](https://orcid.org/0000-0003-3819-3445) for publication details.

## Contact

Contact me by [email](mailto:f.preti@protonmail.com) or
[LinkedIn](https://www.linkedin.com/in/francesco-preti/).
