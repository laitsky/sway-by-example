---
sidebar_position: 2 
---

# Tools Installation

To start developing with Sway language, there are tools you need to install. There are two points need to be taken:
- Sway toolchain will suffice if the need is only to compile the smart contract;
- Fuel Core node will be required if you need to run the smart contract, this includes for testing. Fuel toolchain will have both core node and sway toolchain.

To install Fuel toolchain, there exist a `fuelup` — a Fuel toolchain manager (similar functionalities with `rustup`). User can start install them by running the curl command below:
```
curl --proto '=https' --tlsv1.2 -sSf \
    https://fuellabs.github.io/fuelup/fuelup-init.sh | sh
```

To make sure the toolchain manager `fuelup` is properly installed, run the command `fuelup -V` in your terminal and look for the output. If it shows some number then you're good to go! 

If there is a need to update the toolchain, you can run the command `fuelup toolchain install latest` or `fuelup update`. 

Use `fuelup check` to see if your tools are up to date. To update `fuelup`, you can run the command `fuelup self update`. 

You can also install the toolchain from the source by referring to the official documentation page [here](https://fuellabs.github.io/fuelup/master/installation/index.html).