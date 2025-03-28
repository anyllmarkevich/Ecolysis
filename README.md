[![Rust](https://github.com/gallus-gallus/EcolysisCMD/actions/workflows/rust.yml/badge.svg)](https://github.com/gallus-gallus/EcolysisCMD/actions/workflows/rust.yml)
![crates.io](https://img.shields.io/crates/v/ecolysis_core.svg)
# Ecolysis: simulation and analysis of ecological systems
This project, written in Rust, aims to provide a modern and optimized toolset for ecological simulation and analysis through command-line interfaces, libraries, and, eventually, a GUI for ecologists and managers.

**Status:** This project is in its earliest stages. Current short-term goals are:
- [x] Provide low-compute-cost Population Viability Analysis using population-level simulation.
- [ ] Provide forward simulation of population dynamics and genetic diversity using individual-level simulation, targeting predictive modeling of organisms for reintroduction programs.

**Ultimate Goal:** Provide ecological simulation and modelling tools for ecologists and managers, implemented in a user-friendly UI, specifically emphasizing accessibility for nonprofit and community conservation applications.

**Open Source!** Feel free to contribute, provide bug reports, etc.

## Implementations
### Crates

Crates are the equivalent of packages in Rust. You can learn more about each crate in the README file in the crate's folder.
- [ecolysis_core](https://crates.io/crates/ecolysis_core): core functionality and logic for the project

### Other

Ecolysis is in development as an R package in the [recolysis](https://github.com/anyllmarkevich/recolysis/) repo, although that repo only contains the code to interface with R as the underlying logic comes from the [ecolysis_core](https://crates.io/crates/ecolysis_core) crate (in this repo).

# Installation Instructions
[ecolysis_core](https://crates.io/crates/ecolysis_core) is avaialble on crates.io!

# Build Instructions
Check if Rust is installed by running `rustc --version` in your Command Line Interface. If you do not see a version number, [install Rust](https://www.rust-lang.org/tools/install) onto your system.
### Git Clone
Check if Git is installed by running `git --version` in your Command Line Interface. If you do not see a version number, [install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) onto your system.

Use your Command Line Interface to navigate to the file location where you want to save the project files (`cd ~/filepath/` on Linux, Mac, or Powershell on Windows; `cd %USERPROFILE%\filepath\` on older Windows systems).

Run `git clone https://github.com/gallus-gallus/Ecolysis.git` in your Command Line Interface. The project files are now saved on your computer.

Use your Command Line Interface to navigate into the project folder (`cd Ecolysis` on most systems).

To run ecolysis, you can use `cargo run` in your Command Line Interface, using the `-p` flag to run a specific crate within the workspace (for example, `cargo run -p ecolysis_core`). The `cargo build --release` command will create optimized binaries for your system (use the `-p` flag to only build a specific crate instead of the entire workspace), found under `~/yourpath/ecolysis/target/release/[crate].[executable extension]` (Linux, Mac, Powershell Windows) or `%USERPROFILE%\yourpath\ecolysis\target\release\[crate].[executable extension]` (older Windows).
### Download Files
Download the project files by clicking the green "code" button at the top of this page. Select "Download ZIP" at the bottom of the dropdown. Unzip the downloaded file and save it to a location of your choice.

Use your Command Line Interface to navigate to the file location where you unzipped the project files, and enter the project folder (`cd ~/filepath/EcolysisCMD-main/` on Linux, Mac, or Powershell on Windows; `cd %USERPROFILE%\filepath\EcolysisCMD-main\` on older Windows systems).

To run the program, you can use `cargo run` in your Command Line Interface, using the `-p` flag to run a specific crate within the workspace (for example, `cargo run -p ecolysis_core`). The `cargo build --release` command will create optimized binaries for your system (use the `-p` flag to only build a specific crate instead of the entire workspace), found under `~/yourpath/ecolysis/target/release/[crate].[executable extension]` (Linux, Mac, Powershell Windows) or `%USERPROFILE%\yourpath\ecolysis\target\release\[crate].[executable extension]` 

# Other Software
Need something else? Check out our [Other Software](https://github.com/gallus-gallus/EcolysisCMD/wiki/Similar-Software) wiki page for a list of related software packages!
