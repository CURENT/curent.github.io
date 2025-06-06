---
layout: single
title: "Getting Started"
excerpt: "A quick start guide for new users."
permalink: /getting-started/
share: true
related: fasle
date: 2024-01-08
last_modified_at: 2025-06-05
comments: true
show_date: false
toc: true
toc_sticky: true
---
This page provides a quick start guide for new users to get started with LTB.
Each project has its own documentation, where more details about installation and example usage can be found.

## Installation

### Operating System

LTB projects are designed to be cross-platform and are compatible with Windows, macOS, and Linux. Note that [Windows Subsystem for Linux (WSL)][WSL] can be easier to use on Windows.

### Environment Configuration

If you are new to Python and want to get started quickly, you can use Mambaforge, which is a conda-like package manager configured with conda-forge.

First, install Mambaforge.

Download the latest Mambaforge for your platform from conda-forge/miniforge.
Most users will use x86_64(amd64) for Intel and AMD processors.
Mac users with Apple Silicon should use arm64(Apple Silicon) for best performance.

Next, complete the Mambaforge installation on your system.
If you are using Anaconda or Miniconda on Windows, you should open Anaconda Prompt instead of Miniforge Prompt.

Second, create an environment for LTB.

Open Terminal (on Linux or macOS) or Miniforge Prompt (on Windows, not cmd!!).
Make sure you are in a conda environment - you should see (base) prepended to the command-line prompt, such as ``(base) C:\Users\username>``

Create an environment for LTB (recommended), you can change the environment name `<ltb>`.

```bash
mamba create --name ltb
```

Activate the new environment with

```bash
mamba activate ltb
```

You will need to activate the ltb environment ***every time*** in a new Miniforge Prompt or shell.
If you have completed these steps without error, you now have a working Python environment. See the commands at the top for Getting started.

### Package Installation

There are two modes of installation: development and release.

#### Release Mode

Regular releases are available on distribution channels such as PyPI and conda-forge.

#### Development Mode

For model development purpose, you may want to install the latest version and play with the source code.

[Develop Install](https://andes.readthedocs.io/en/latest/getting_started/install.html#develop-install) discusses how to install ANDES in development mode.
It is also applicable to AMS and AGVis.

## Hands-on Tutorial

It is recommended to go through [ANDES Examples](https://andes.readthedocs.io/en/latest/examples/index.html) and [AMS Examples](https://ltb.readthedocs.io/projects/ams/en/latest/examples/index.html) to get familiar with the LTB usage.

[LTB Demo](https://github.com/CURENT/demo) is a collection of Jupyter notebooks that demonstrate the usage of LTB projects.
