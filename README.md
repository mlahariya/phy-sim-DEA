Code and data for the research paper titled “Learning physics-informed simulation models for soft robotic manipulation: A case study with dielectric elastomer actuators”, authored by 
[Manu Lahariya](https://mlahariya.github.io/), [Craig Innes](http://www.craiginnes.com/), [Chris Develder](http://users.atlantis.ugent.be/cdvelder/) and [Subramanian Ramamoorthy](https://www.edinburgh-robotics.org/academics/subramanian-ramamoorthy).

To be presented at [IROS 2022](https://iros2022.org/)

## Abstract
Soft actuators offer a safe, adaptable approach to tasks like gentle grasping and dexterous manipulation. Creating accurate models to control such systems however is challenging due to the complex physics of deformable materials. Accurate Finite Element Method (FEM) models incur prohibitive compu- tational complexity for closed-loop use. Using a differentiable simulator is an attractive alternative, but their applicability to soft actuators and deformable materials remains under- explored. This paper presents a framework that combines the advantages of both. We learn a differentiable model consisting of a material properties neural network and an analytical dynamics model of the remainder of the manipulation task. This physics-informed model is trained using data generated from FEM, and can be used for closed-loop control and inference. We evaluate our framework on a dielectric elastomer actuator (DEA) coin-pulling task. We simulate the task of using DEA to pull a coin along a surface with frictional contact, using FEM, and evaluate the physics-informed model for simulation, control, and inference. Our model attains ≤ 5% simulation error compared to FEM, and we use it as the basis for an MPC controller that requires fewer iterations to converge than model-free actor-critic, PD, and heuristic policies.

## Citation
    @misc{https://doi.org/10.48550/arxiv.2202.12977,
      doi = {10.48550/ARXIV.2202.12977},
      url = {https://arxiv.org/abs/2202.12977},
      author = {Lahariya, Manu and Innes, Craig and Develder, Chris and Ramamoorthy, Subramanian},
      keywords = {Robotics (cs.RO), Artificial Intelligence (cs.AI), FOS: Computer and information sciences, FOS: Computer and information sciences},
      title = {Learning physics-informed simulation models for soft robotic manipulation: A case study with dielectric elastomer actuators},
      publisher = {arXiv},
      year = {2022},
    }

## Acknowledgment
This research was performed by M. Lahariya from the [AI for Energy Research Group](https://ugentai4e.github.io/) at [IDLAB, UGent-imec](https://www.ugent.be/ea/idlab/en) in colloboration with [Robust Autonomy and Decisions Group](https://rad.inf.ed.ac.uk/), University of Edinburgh.
## Contact
If you have any questions, please contact me at manu.lahariya@ugent.be