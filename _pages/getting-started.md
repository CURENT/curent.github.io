---
layout: single
title: "Getting Started"
excerpt: "A quick start guide for new users."
permalink: /getting-started/
share: true
related: false
date: 2024-01-08
last_modified_at: 2025-06-05
comments: true
show_date: false
toc: true
toc_sticky: true
---
This page provides a quick start guide for new users to get started with LTB.
Each project has its own documentation, where you can find more details about installation and example usage.

## Installation

### Operating System

LTB projects are designed to be cross-platform and are compatible with Windows, macOS, and Linux. Note that [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install) can be easier to use on Windows.

### Environment Configuration

If you're new to Python and want to get started quickly, we recommend using **Mambaforge**, a conda-like package manager configured with conda-forge.

#### Step 1: Install Mambaforge

Download the latest Mambaforge installer for your platform from the [conda-forge/miniforge](https://conda-forge.org/download/) page.

- Most users with Intel or AMD processors should choose the **x86_64 (amd64)** version.
- Mac users with Apple Silicon should choose the **arm64 (Apple Silicon)** version for best performance.

After downloading, complete the installation following the instructions for your operating system.

> **Note:** If you're using Anaconda or Miniconda on Windows, open the **Anaconda Prompt**, not the **Miniforge Prompt**.

#### Step 2: Create an Environment for LTB

Open **Terminal** (on Linux or macOS) or **Miniforge Prompt** (on Windows — not `cmd`!).

Ensure you're in a conda environment — you should see `(base)` at the beginning of your command prompt, e.g., `(base) C:\Users\username>`.

To create a new environment for LTB (you can change the name `ltb` if desired):

Create an environment for LTB (recommended), you can change the environment name `<ltb>`.

```bash
mamba create --name ltb
```

Activate the new environment:

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

We recommend exploring the following examples to get familiar with LTB:

- [ANDES Examples](https://andes.readthedocs.io/en/latest/examples/index.html)
- [AMS Examples](https://ltb.readthedocs.io/projects/ams/en/latest/examples/index.html)

You can also check out the [LTB Demo](https://github.com/CURENT/demo), a collection of Jupyter notebooks demonstrating the usage of LTB projects.
