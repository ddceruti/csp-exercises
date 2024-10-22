# Interactive Exercises on Concentrating Solar Thermal Power Plants

## Description

This repository contains five exercises for the lecture "Concentrating Solar
Power Plants" at TU Munich to learn about CSP interactively. The exercises are
interactive and will be corrected in the exercise sessions.

### Exercise 1: Weather Data

Getting started, dealing with weather data and the obtaining the renewable
energy potentials for CSP.

To download weather locations globally:

- Bayern: .epw <https://climate.onebuilding.org/WMO_Region_6_Europe/DEU_Germany/index.html#IDBY_Bayern->
- Europe: .epw <https://climate.onebuilding.org/WMO_Region_6_Europe/default.html>

### Exercise 2: The Global CSP Industry

Data science exercise to analyse the global CSP Overview of CSP plants
thanks to the [CSP.guru](https://csp.guru/) dataset. For the original paper
and analysis please go to the references:

>Lilliestam J, Ollier L, Labordena M, Pfenninger S, Thonig R. The near-to mid-term outlook for concentrating solar power: mostly cloudy, chance of sun. Energy Sources, Part B: Economics, Planning, and Policy. 2021 Jan 2;16(1):23-41. [https://doi.org/10.1080/15567249.2020.1773580](https://doi.org/10.1080/15567249.2020.1773580)

> Richard Thonig, & Johan Lilliestam. (2023). CSP.guru (Version 2023-07-01) [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.1318151](https://doi.org/10.5281/zenodo.1318151)

### Exercise 3: Simulation of a Steam Rankine Cycle

TESpy simulation of a basic [steam rankine cycle](https://github.com/oemof/tespy/blob/dev/tutorial/basics/rankine.py).

### Exercise 4: Simulation of Andasol II Power Plant

TESpy simulation of the steam rankine cycle of the [Andasol II](https://solarpaces.nrel.gov/project/andasol-2)
parabolic trough power plant with the conditions from this
[paper](https://doi.org/10.1016/j.jprocont.2016.01.002).

> Al-Maliki WA, Alobaid F, Kez V, Epple B. Modelling and dynamic simulation of a parabolic trough power plant. Journal of process control. 2016 Mar 1;39:123-38. [https://doi.org/10.1016/j.jprocont.2016.01.002](https://doi.org/10.1016/j.jprocont.2016.01.002)

### Exercise 5: Simulation of a Supercritical CO2 Power Cycle

Simulation of a [supercritical CO2 power cycle](https://sco2symposium.com/papers2018/cycles/052_Paper.pdf).

> Penkuhn M, Tsatsaronis G. Exergoeconomic analyses of different sCO2 cycle configurations. InProceedings of the 6th International Symposium—Supercritical CO2 Power Cycles, Pittsburgh, PA, USA 2018 Mar (pp. 27-29). [https://sco2symposium.com/papers2018/cycles/052_Paper.pdf](https://sco2symposium.com/papers2018/cycles/052_Paper.pdf)

## Installing

### Prerequisites

- [Git](https://git-scm.com/downloads): Optional but recommended.
- [Miniconda3](https://docs.anaconda.com/free/miniconda/index.html)
- Choose an option for GUI of Python & Jupyter (suggestions):
  - [Visual Studio Code](https://code.visualstudio.com/) (recommended)
  - [Spyder](https://www.spyder-ide.org/>)
  - [pycharm](https://www.jetbrains.com/pycharm/)
  - or any other GUI for Python
- Install the Jupiter & Python exctension for your GUI

### Download the Files

#### Option A: Clone Repository (Git CMD)

1. Open Git CMP window
2. Open any folder (in explorer) where the repository should be store
3. Navigate with the git command prompt to this folder: cd 'c:/path/to/folder'
4. Clone downloaded repository with git: git clone 'url'
5. exit Git CMD

#### Option B: Download .zip

Alternatively, you can download the repository as a .zip and extract the files.

### Install Required Packages

1. Open the Anaconda Powershell Prompt
2. Navigate to the cloned repository and copy path of folder in explorer: cd  'c:/path/to/folder/csp_exercises'
3. Create a new environment `conda create -n csp python=3.11`
4. Activate the environment `conda activate csp`
5. Install all required packages `pip install -r requirements.txt` (can take a while to finalize)
6. check installed packages with command `conda list` (especially check for 'notebook')

## Getting Started

The best way to solve the exercises is to open the notebook and try to run all cells.
Then the exercises can be done within each "empty" jupyter notebook file, where the questions can be answered
directly in the empty cells below.

Here is the workflow:

0. Install a Text editor of your choice (VS Code,Spyder, ect.)
1. Open the Anaconda Powershell Prompt
2. Activate environment `conda activate csp`: always switch to this environment, otherwise you can damage the (base) path and you have to re-install all from scratch
3. Launch jupyter-notebook `jupyter notebook`: <https://docs.jupyter.org/en/latest/running.html>
4. Navigate to file and run all cells: <https://saturncloud.io/blog/Jupyter-notebook-run-all-cells-a-comprehensive-guide/>
5. Stop jupyter server to run press 'ctrl+c' two times

## Documentation on Key Packages

### pandas

<https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide>
<https://pandas.pydata.org/docs/user_guide/10min.html#min>
<https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf>
<https://pandas.pydata.org/docs/getting_started/tutorials.html#communitytutorials>

### matplotlib

<https://matplotlib.org/stable/api/pyplot_summary.html>

### folium

<https://python-visualization.github.io/folium/latest/getting_started.html>

### .ewp (Energy Plus Weather File)

<https://climate.onebuilding.org/papers/EnergyPlus_Weather_File_Format.pdf>

### tespy

<https://tespy.readthedocs.io/en/main/introduction.html>

## Authors

In alphabetic order:

- Ammerer, Maximilian (TUM)
- Ceruti, Amedeo (TUM)

## Contribute

Contributions are welcome. Please post an issue or a pull request.

## License

[MIT License](https://en.wikipedia.org/wiki/MIT_License)
