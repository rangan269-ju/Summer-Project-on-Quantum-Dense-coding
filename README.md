# Summer Project on Quantum Dense Coding
![Python](https://img.shields.io/badge/Python-3.11-blue)
![Qiskit](https://img.shields.io/badge/Qiskit-Latest-6929C4)
![IBM Quantum](https://img.shields.io/badge/IBM-Quantum-1261FE)
![License](https://img.shields.io/badge/License-GPL%20v3-blue)


This repository contains the implementation, simulation codes, and supporting materials developed during my summer research project work at IISER Bhopal, India on **Quantum Dense Coding Using Bipartite and Multipartite Entangled States Over Noiseless and Noisy Quantum Channels: An IBM Quantum Experience**. The project investigates the performance of dense coding protocols using different entangled quantum channels under both ideal and noisy quantum environments.

The simulations are implemented using **Python** and **Qiskit**, with a focus on understanding the influence of realistic quantum noise on communication efficiency and protocol robustness.

---

## Project Objectives

* Study the fundamentals of quantum dense coding.
* Implement dense coding protocols using different entangled states.
* Analyze protocol performance under ideal conditions.
* Investigate the effects of Pauli noise channels.
* Compare different entangled resources based on communication capacity, efficiency, and robustness.
* Validate theoretical results through numerical simulations.

---

## Entangled States Studied

The repository includes implementations and analyses for:

* Bell State
* Three-Qubit GHZ State
* Four-Qubit Cluster State
* Five-Qubit Cluster State
* Six-Qubit Cluster State

---

## Noise Models

The protocols are evaluated under several realistic quantum noise models, including:

* Bit Flip Channel
* Phase Flip Channel
* Bit-Phase Flip Channel

Performance metrics such as fidelity, success probability, communication efficiency etc. are computed and compared.

---

## Repository Structure

```text
Summer-Project-on-Quantum-Dense-coding/
│
├── Bell_State/
├── GHZ_State/
├── Cluster_States/
├── Noise_Models/
├── Figures/
├── Report/
├── Results/
└── README.md
```

> *The folder names may vary slightly depending on future updates.*

---

## Technologies Used

* Python
* Qiskit
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Highlights

* Analytical derivation of quantum dense coding protocols.
* Qiskit-based simulation of multiple entangled channels.
* Comparative study under different Pauli noise models.
* Performance evaluation using various communication metrics.
* Reproducible simulation framework for quantum communication research.

---

## Results

The study demonstrates that:

* Theoretical predictions agree closely with simulation results.
* Different entangled channels exhibit different levels of robustness against quantum noise.
* Increasing circuit depth and gate complexity generally reduce protocol performance in noisy environments.
* Cluster-state-based protocols provide higher communication capacity, whereas Bell-state protocols exhibit superior robustness under certain noise models.

---

## Requirements

Install the required Python packages:

```bash
pip install qiskit numpy matplotlib
```

or

```bash
pip install -r requirements.txt
```

if a `requirements.txt` file is provided.

---

## Future Work

Possible extensions include:

* Implementation on IBM Quantum hardware.
* Study of amplitude damping and depolarizing channels.
* Error mitigation techniques.
* Controlled and probabilistic dense coding.
* Qudit-based dense coding protocols.

---

## Citation

If you use this repository in your research, please cite it as:

```bibtex
@misc{chakrabarty2026qdc,
  author       = {Rangan Chakrabarty},
  title        = {Summer Project on Quantum Dense Coding},
  year         = {2026},
  howpublished = {\url{https://github.com/rangan269-ju/Summer-Project-on-Quantum-Dense-coding}}
}
```

---

## Author

**Rangan Chakrabarty**
Email ID: [![Email](https://img.shields.io/badge/Email-rangan269@gmail.com-red?logo=gmail&logoColor=white)](mailto:rangan269@gmail.com)
B.Sc. (Hons.) Physics
Jadavpur University, India

---

## License

This project is licensed under the **GPL-V3.0 License**. See the `LICENSE` file for details.
