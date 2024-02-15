# Costa Rica RISC-V Lab

Welcome to the Costa Rica RISC-V Lab.

This RISC-V Lab provides access to riscv64 hardware for compiling and testing of software, via methods like GitHub runners and others if requested.

![Costa Rica RISC-V Lab](docs/img/logo-med.png)


If you need access, please fill an Issue with the following information:
- Email contact information
- URL for the project you represent
- Any particular requirements such as distro versions, access method (GitHub runner, GitLab runner, Jenkins, etc)

## Current projects

This are some of the projects who currently have access to the Costa Rica RISC-V Lab's resources.

| Project | Description | Hosts in use | Active |
|---------|-------------|--------------|--------|
| [Mariner](https://github.com/fede2cr/CBL-Mariner) | Azure Linux unofficial port for riscv64| lichee01-08ram64sd |✅|
| [Slackware](https://github.com/fede2cr/slackware_riscv) | Slackware Linux official port for riscv64 | lichee01-08ram64sd |✅|
| [Python whl](https://github.com/fede2cr/riscv64-python-whl) | Release of python modules as riscv64 whl binaries | lichee01-08ram64sd, lichee02-08ram32sd |✅|
| Eclipse Adoptium | OpenJDK binaries for riscv64 | lichee02-08ram32sd | ✅ |

## Inventory

| Board count | Board | Core count | RAM in gibi | Disk in gibi | Installed | Runner ready |
|------------:|-------|-----------:|------------:|-------------:|-----------|--------------|
| 2           | Lichee Pi 4a|    4 |            8|           96 |        2/2|          2/2 |
| 1           | VisionFive 2|    4 |            8|           64 |        1/1|          1/1 |
| 1           | VisionFive 1|    2 |            8|              |        0/1|          0/1 |
| 2           | BeagleV     |    1 |            8|              |        0/2|          0/2 |
| 8           | Mango MQ    |    1 |            1|          224 |        4/8|          4/8 |
| 2           | Lichee RV Dock|  1 |            1|              |        0/2|          0/2 |
| 1           | Nezha         |  1 |            1|           64 |        1/1|          1/1 |
| 1           | PineTab-V      |  4 |           4 |           64 |        0/1|          0/1 |
| 1           | MilkV Pioneer | 64 |         128 |           NA |        0/1|          0/1 |
| 1           | MilkV Mars    |  4 |           8 |           NA |        0/1|          0/1 |
| Totals      |        |            |             |              |           |              |
| 20          | 10     |         99 |         191 |          576 |       8/20|         8/20 |

## Distributions report

| Board | Bare metal distro | Kernel version | Notes |
|-------|-------------------|---------------:|-------|
| Lichee Pi 4a | revyos sid | 5.10.113-g7b352f5ac2ba | Has GUI, use ansible to remove packages and configure storage: Can't boot from SD and flash is only 8G. |
| VisionFive2 | [Armbian 23.8 Lunar](https://www.armbian.com/visionfive2/) | 5.15.0-starfive | Serial console needed. |
| MangoPi | Armbian 22.08 Jammy | 5.19.0-rc1-d1 | Serial console needed. Net via wifi. No nodejs. |
| PineTab-V | star64-image-plasma | 5.15.107 | Cannot be assigned for projects, only for quick testing. | 
| Pioneer | NA | NA | Setup in progress. |
| Mars | NA| NA| Setup in progress. |

## Official Status

The lab is undergoing submit/review by the RISC-V Labs working group, and currently does not have an official RISC-V Lab status.

## Location

The Costa Rica RISC-V Lab is located inside a beautiful dry forest in Esparza, Puntarenas; preserved by 5 generations and surounded by [nature](https://www.inaturalist.org/projects/biodiversidad-en-esparza).
