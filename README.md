### QRISE IBM Challenges [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Python version 3.9](https://img.shields.io/badge/python-v3.9-brightgreen)](https://docs.python.org/3/whatsnew/3.9.html)

[Proposal Title](#proposal-title) | [Problem Statement](#problem-statement) | [Project Objective](#project-objective) | [contributors](#contributors) | [Literature Survey](literature_survey.md) | [Implementation details](austism) | [Project Report](prompt/report.pdf) | [Project Slides](prompt/ppt.pdf) | [Details](https://youtu.be/uIKkJragaoU?si=E95tmCCPxxCMWNke) | [Conclusion](#conclusion) |

The implementation of the project can be accessed via the following link: [here](implementation/notebbok).<br>
Also access the implemented [Project report](austism/penn.ipynb).

### Contributors:

| Author           | Linkedin profile                                 |
|------------------|-------------------------------------------------|
| Shisheer S Kaushik(M23IQT0063) | [Kaushik](https://www.linkedin.com/in/shisheerkaushik24/) | 
| Thirumalai M(M23IQT008)| [Thiru](https://www.linkedin.com/in/m-thirumalai/?originalSubdomain=in)| 
                                                      
#### Project Title

*From Static to Dynamic: Implementation of Long range Entanglement GHZ states for Dynamic Circuit-Based Quantum Teleportation*

#### Project Statement

In many domains, quantum computing has demonstrated its superiority over classical computing, and it continues to expand. It has demonstrated exponential speedups compared to the classic approach in certain problems. Nevertheless, scalability and noisy environments remain challenges for quantum hardware. In contrast to the unitary dynamics that characterize quantum circuits, recent research has introduced dynamic circuits with non-unitary dynamics. Dynamic circuits include mid-circuit measurement and conditional feed forward operations, which are discussed in this study along with long-range entanglement and a quantum teleportation protocol. Mid-circuit measurement not only allows for the utilization of the corresponding qubit for other operations, but also diminishes circuit depth, thereby contributing to a less noise environment.Mid-circuit measurements enable the efficient implementation of fault-tolerant logical operations, measurement-based quantum computation, and quantum error correction. Quantum computers will be scaled and much more efficiently operated with dynamic circuits.

#### Project Objective

- **1: Enhancing Error Reduction**: Implementing dynamic circuits post-teleportation aims to significantly reduce error rates in quantum teleportation processes. By utilizing feed-forward operations and dynamic circuitry, errors are minimized, ensuring more accurate teleportation outcomes.

- **2: Scaling to Multi-Qubit Teleportation**: The project aims to scale up quantum teleportation protocols to support multi-qubit teleportation. By increasing the number of qubits involved in the teleportation process, the project seeks to demonstrate the feasibility and efficacy of teleporting complex quantum states across multiple qubits.

- **3: Maintaining Circuit Depth and Efficiency**: Through the use of dynamic circuits, the project aims to maintain a constant circuit depth even as the number of qubits increases. This ensures efficient quantum teleportation operations while mitigating the potential increase in errors and time consumption associated with traditional approaches.

- **4: Demonstrating the Role of Dynamic Circuits**: The project seeks to demonstrate the critical role of dynamic circuits in enabling successful quantum teleportation with an expanding number of qubits. By showcasing the reduction in error rates and circuit depth achieved through dynamic circuitry, the project highlights the significance of this approach in advancing quantum teleportation technology.


**First steps to run locally**

Create a conda environment with the required dependencies:
```bash
conda env create -n quantumproj environment.yml && conda activate IBMQRISEproj
```
<br>
  
Alternatively, one can install the required dependencies via the [package_list.txt](package_list.txt) file:
```bash
conda create -yn quantumproj python==3.9.11 && conda activate quantumproj
```
```bash
conda update -yn base -c defaults conda && conda install -yc conda-forge pip==22.1.2
```
```bash
python3 -m pip install --user --upgrade pip && python3 -m pip install -r requirements.txt
```

## Contributions:
Contributions to the repository are always welcome! If you have any ideas for new projects or would like to contribute to an existing one, please feel free to open a pull request.

# License

This work is licensed under a [Apache v2.0](LICENSE) license.

<hr>

Created and maintained by [@Shisheer S Kaushik][1].

[1]: https://github.com/ShisheerKauhik24
