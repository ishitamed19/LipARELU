# LipARELU: A-ReLU Networks aided by Lipschitz Acceleration


By [Ishita Mediratta](https://github.com/ishitamed19), [Snehanshu Saha](https://www.bits-pilani.ac.in/goa/snehanshus/profile), [Shubhad Mathur](https://github.com/frontseat-astronaut).

Official implementation of ["LipARELU: A-ReLU Networks aided by Lipschitz Acceleration"](https://ieeexplore.ieee.org/abstract/document/9533853), accepted to **IJCNN 2021 (Oral)**.

## Usage

For each task, either `classification` or `regression`, go to its corresponding subfolder. To train a model with a given loss type, run the entire jupyter notebook.

Loss types supported are:
|                      | Classification | Regression |
|----------------------|----------------|------------|
| MAE                  | ✅              | ✅          |
| Binary/Cross-Entropy | ✅              | ⛔️          |
| Quadratic Loss       | ⛔️              | ✅          |
