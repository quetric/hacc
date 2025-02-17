<div id="readme" class="Box-body readme blob js-code-block-container">
<article class="markdown-body entry-content p-3 p-md-6" itemprop="text">
<p align="right">
<a href="https://github.com/fpgasystems/hacc#--heterogenous-accelerated-compute-cluster">Back to top</a>
</p>

# Features

## CLI
With ETHZ-HACC [CLI](../cli/README.md#cli), you can easily:

* Validate the basic HACC infrastructure functionality (see [Infrastructure validation](./infrastructure-validation.md)),
* Transition between [Vivado and Vitis workflows](#vivado-and-vitis-workflows),
* Learn about model-based design by making use of our *out-of-the-box* [Examples](./examples.md#examples),
* Create your own Vivado or Vitis projects based on multiple-choice dialogs and templates—helping you to develop your accelerated applications more quickly, 
* Design, build, and deploy modern FPGA-accelerated applications on top of our [Infrastructure for heterogeneous architectures and hardware acceleration](https://systems.ethz.ch/research/data-processing-on-modern-hardware/hardware-acceleration-infrastructure.html) platform (including ACCL, Coyote, or EasyNet),
* *Et cetera.*

## Vivado and Vitis workflows
Thanks to our [PCI hot-plug](./vocabulary.md#pci-hot-plug) process, we are able to transition between the [Vivado and Vitis workflows](./vocabulary.md#vivado-and-vitis-workflows) without the need of rebooting the system.

## Managed
We use [Infrastructure as Code (IaC)](./vocabulary.md#infrastructure-as-code-iac) and [Ansible Automation Platform (AAP)](./vocabulary.md#ansible-automation-platform-aap) to [operate the cluster](../docs/operating-the-cluster.md#operating-the-cluster) efficiently. Under the scope of a [DevOps](./vocabulary.md#devops) methodology, we achieve the following: <!-- https://docs.microsoft.com/en-us/devops/deliver/what-is-infrastructure-as-code -->

* Continuos delivery,
* Avoid manual configuration to enforce consistency,
* Use declarative definition files helping to document the cluster,
* Easily follow Xilinx’s tools versioning release schedule, and
* Deliver stable tests environments rapidly at scale.

## You are welcome
We are glad and welcome you every time you login to one of our servers. Behind the scenes, our *welcome_msg* script performs the following functions:

* Runs a sanity check to verify the correct functioning of the operating system, as well as hardware and software related to Xilinx accelerators,
* Helps you to choose your environement regarding [Vivado and Vitis workflows](./vocabulary.md#vivado-and-vitis-workflows),
* It gives you derived information regarding the active *Xilinx release branch, tools, and flashable partitions running on FPGA,* as well as the network information that might be relevant for your accelerated applications,
* *Et cetera.*