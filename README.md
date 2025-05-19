# STRAINER-INR
Codebase for Learning Transferable Features for Implicit Neural Representations (NeurIPS'24) **(Coming soon!)**

[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/4a8bc86ca475c229dc1fd0f4d5cf8f63-Abstract-Conference.html) | [arXiv](https://arxiv.org/abs/2409.09566) | [Project Page](https://kushalvyas.github.io/strainer.html) | [Colab](https://colab.research.google.com/drive/1fBZAwqE8C_lrRPAe-hQZJTWrMJuAKtG2?usp=sharing)


__Abstract__: Implicit neural representations (INRs) have demonstrated success in a variety of applications, including inverse problems and neural rendering. An INR is typically trained to capture one signal of interest, resulting in learned neural features that are highly attuned to that signal. Assumed to be less generalizable, we explore the aspect of transferability of such learned neural features for fitting similar signals. We introduce a new INR training framework, STRAINER that learns transferable features for fitting INRs to new signals from a given distribution, faster and with better reconstruction quality. Owing to the sequential layer-wise affine operations in an INR, we propose to learn transferable representations by sharing initial encoder layers across multiple INRs with independent decoder layers. At test time, the learned encoder representations are transferred as initialization for an otherwise randomly initialized INR. We find STRAINER to yield extremely powerful initialization for fitting images from the same domain and allow for a ≈ +10dB gain in signal quality early on compared to an untrained INR itself. STRAINER also provides a simple way to encode data-driven priors in INRs. We evaluate STRAINER on multiple in-domain and out-of-domain signal fitting tasks and inverse problems and further provide detailed analysis and discussion on the transferability of STRAINER’s features.


## Setup and Installation


## Running STRAINER


## STRAINER Visualization script



## Citation:
If you find this code useful, please consider citing the paper.

    @inproceedings{vyas2024strainer,
      author = {Vyas, Kushal and Humayun, Ahmed Imtiaz and Dashpute, Aniket and Baraniuk, Richard G. and Veeraraghavan, Ashok and Balakrishnan, Guha},
      booktitle = {Advances in Neural Information Processing Systems},
      editor = {A. Globerson and L. Mackey and D. Belgrave and A. Fan and U. Paquet and J. Tomczak and C. Zhang},
      pages = {42268--42291},
      publisher = {Curran Associates, Inc.},
      title = {Learning Transferable Features for Implicit Neural Representations},
      url = {https://proceedings.neurips.cc/paper_files/paper/2024/file/4a8bc86ca475c229dc1fd0f4d5cf8f63-Paper-Conference.pdf},
      volume = {37},
      year = {2024}
    }
