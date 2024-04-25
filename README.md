## Description
LightningLite is a project that realizes Pytorch-lightning in minimal, readable and customizable codes. This repository implements 3 necessary components for any deep learning experiments:
1. Module: A wrapped class for augmenting the abilities of original torch model adding more details about how to do before/on/after training/validation/test.
2. Trainer: A general training processor, capable for any tasks.
3. DataModule: A wrapped class which tells trainer the details about how to load dataset for training/validation/test.

## submodule
1. Logger: Logging system is the key to any scientific experiment. It allows user to persist experimental data on disk for later research. This module is included in the Trainer module by default. However, it can be used independently.
2. Printer: Beside Logger, user wants to know real-time result of current experiment. Printer formats all results and puts them on console.
3. Timer: Time recording is also a key to scientific experiment. This module adds timing capability to Trainer.

## How it works



## Installation

1. clone this repository in your project
2. directlry import the module you need

