# RISC-V Reference SoC Tapeout Program VSD

## Tools Installation

---

**All the instructions for installation of required tools can be found here:**

### System Requirements
- 6 GB RAM
- 50 GB HDD
- Ubuntu 20.04 or higher
- 4 vCPU

### TOOLS CHECK
### 1. YOSYS

```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make (If make is not installed please install it)
$ sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install
```
<img width="912" height="595" alt="image" src="https://github.com/user-attachments/assets/8bede7d6-a3e5-43f4-b06f-0afa9b5d0e81" />

### 2. IVERILOG

```bash
sudo apt-get update
sudo apt-get install iverilog
```
<img width="916" height="672" alt="image" src="https://github.com/user-attachments/assets/15970ba5-1908-476c-8bcd-9aedc3cac9d9" />

### 3. GTKWAVE

```bash
sudo apt-get update
sudo apt install gtkwave
```
<img width="689" height="131" alt="image" src="https://github.com/user-attachments/assets/665dbe9a-42d0-4b48-9915-26eeb937362f" />








