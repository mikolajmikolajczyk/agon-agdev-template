# Agon AgDev Template

This repository provides a simple template for starting AgDev Agon projects. It includes basic structure and configurations to help you kickstart your project quickly.

## Prerequisites

1. **AgDev Toolchain**: Make sure the AgDev toolchain from pcawte/AgDev is installed and available in your `PATH`.
2. **agon-hexload**: Clone the agon-hexload repository next to this template to enable the `make send` command.

## Usage

1. Clone this repository (or fork via github)

```sh
git clone https://github.com/mikolajmikolajczyk/agon-agdev-template.git
```

2. Navigate to the repository directory

```sh
cd agon-agdev-template
```

3. Build the project:

```sh
make
```

4. Send the project to your Agon

```sh
make send
```

If you don't know how to use hexload utility please read [this](https://mikolajczyk.org/posts/agon-hexload-wsl/) post.