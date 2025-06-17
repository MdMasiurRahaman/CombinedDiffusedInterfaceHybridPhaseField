# Combined diffused material interface and hybrid phase-field model for brittle fracture in heterogeneous composites

In this article, we propose a novel approach for modeling brittle fracture in heterogeneous composites using a combined diffused material interface method and a hybrid phase-field model
(PFM). We have used the diffused material interface method to derive analytical expressions for the regularized material properties across the material interfaces that are treated as an
input to the PFM for the simulation of brittle fractures in composites. The use of diffused material interface method regularizes the material properties in such a way that one can avoid
the discontinuity in stress across the material interface and thus bypass the requirement of explicit tracking of material interfaces for finite element implementation of the hybrid PFM. 
We have implemented the proposed combined model using a recently developed open-source finite element toolbox, Gridap in Julia. We have considered tests on a single circular fiber 
inclusion under tension, a bi-material rectangular plate under tension, single square inclusion under tensile loading, a notched composite beam with a central notch under symmetric 
three-point bending, and a rectangular plate with multiple fibers under tensile loading to show how the proposed combined model can be used to simulate brittle fracture in composites.

# See the deatils given by the link below:

https://www.sciencedirect.com/science/article/abs/pii/S0013794422006804

# Cite this article:

@article{prakash2023phase,
  title={A phase-field model for thermo-mechanical fracture},
  author={Prakash, Ved and Behera, Akash Kumar and Rahaman, Mohammad Masiur},
  journal={Mathematics and Mechanics of Solids},
  volume={28},
  number={2},
  pages={533--561},
  year={2023},
  publisher={SAGE Publications Sage UK: London, England}
}
