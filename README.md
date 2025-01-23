# Journey to the Center of the Milky Way: Constraints on the Inner Dark Matter Distribution 

This repository contains code and resources to analyze and visualize results related to the calculations outlined in (Hussein et al 2025). The repository is organized into four main directories, each focusing on a specific aspect of the analysis. Below, you'll find a description of the directories, their purpose, and installation instructions for using this project.

---
## Installation

This project requires Python 3.7 or later. To get started, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/abdelazizhussein/MW-Inner-DM-Profile
cd MW-Inner-DM-Profile
```

### 2. Install Dependencies

The required Python packages are specified in `setup.py`. To install them, run:

```bash
pip install .
```

This will automatically install the following packages:

- `astropy`
- `numpy`
- `matplotlib`
- `scipy`

---

## Directory Structure

### 1. **MW\_Bracketed\_Range** 

- **Description**: This directory contains the code and data necessary to reproduce our bracketed range of the Milky Way's dark matter density profile (grey band in **Figure 2** of the paper). 

### 2. **AC\_calculation**

- **Description**: Implements the calculations outlined in **Appendix D** of the paper. 

### 3. **DM\_Densities**

- **Description**: Contains code to recreate a plot similar to **Figure S-1** in the paper, which visualizes dark matter density profiles for the public simulation suites (Auriga, FIRE-2 and TNG-50).

### 4. **J\_D\_factors**

- **Description**: Provides the calculated **J** and **D factors** as functions of $\theta$.

---



## Usage

Each directory contains specific instructions and example scripts in its `README.md` file (inside the respective folder). 
For detailed explanations of the methodology and code, refer to the comments in the scripts and the accompanying documentation.




