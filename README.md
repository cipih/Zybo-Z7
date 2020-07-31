# Zybo Z7 Root Repository

## Description

This repository is designed to offer a unified and comprehensive approach to all the aspects that we provide, across multiple tools, for the Zybo Z7. By cloning this repo recursively you will receive the repositories for the Vivado project (HW), Vitis workspace (SW) and Petalinux project (OS). Each submodule has it's own submodule dependencies which will be also pulled when cloning. An important aspect of this structure is the fact that both the SW and the OS heavily depend on the hardware hand-off from the HW repository.

Each branch of this repository represents a different project with preset functionality. When checking out a branch, all the submodules will be automatically configured to the same branch, thus providing a unified flow between all the submodules. For details about the individual functionality of the submodules, please refer to the README.md files within the submodules.

For a detailed structural description of this repository and it's submodules, along with the branching system, please visit ~~[Eclypse Z7 Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/eclypse-z7/git)~~.
