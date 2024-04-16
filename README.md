# Asynchronous Heterogeneous Linear Quadratic Regulator Design

This repository includes the Python codes to implement the experimental results of the following paper:

1) L. F. Toso*, H. Wang*, J. Anderson (2024). [Asynchronous Heterogeneous Linear Quadratic Regulator Design](https://arxiv.org/abs/2404.09061)

^* = equal contribution.

## Notation

To ease notation, in the paper we denote the step-size as $\eta$. This is equivalent to $\eta_g \times \eta_l$ in the code, where $\eta_g$ denotes the global step-size (i.e., the step-size used by the server to update the controller) and $\eta_l$ corresponds to the local step-size (i.e., the step-size used to update each system's controller locally). 

## Instructions

To run the codes in this repository, you only need a working Jupyter installation.

## Troubleshooting

If you have any trouble running those codes or have any question about the paper, please email [Leonardo F. Toso](mailto:lt2879@columbia.edu).
