# Interactive Exercises on Concentrating Solar Thermal Power Plants

## Description

This repository contains four exercises for the lecture "Concentrating Solar
Power Plants" at TU Munich to learn about CSP interactively. The exercises are
meant to be solved individually and will be corrected in the classroom during
exercise sessions.

### Exercise 1: Weather Data

Getting started, dealing with weather data and calculating renewable
energy potentials for CSP.

To download weather locations globally, for example:

- Bayern: .epw <https://climate.onebuilding.org/WMO_Region_6_Europe/DEU_Germany/index.html#IDBY_Bayern->
- Europe: .epw <https://climate.onebuilding.org/WMO_Region_6_Europe/default.html>

### Exercise 2: The Global CSP Industry

Data science exercise to analyse the global CSP Overview of CSP plants
thanks to the [CSP.guru](https://csp.guru/) dataset. For the original paper
and analysis please go to the references:

>Lilliestam J, Ollier L, Labordena M, Pfenninger S, Thonig R. The near-to mid-term outlook for concentrating solar power: mostly cloudy, chance of sun. Energy Sources, Part B: Economics, Planning, and Policy. 2021 Jan 2;16(1):23-41. [https://doi.org/10.1080/15567249.2020.1773580](https://doi.org/10.1080/15567249.2020.1773580)

> Richard Thonig, & Johan Lilliestam. (2023). CSP.guru (Version 2023-07-01) [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.1318151](https://doi.org/10.5281/zenodo.1318151)

### Exercise 3: Simulation of Rankine Cycles (Andasol II Power Plant)

TESPy simulation of a basic [steam rankine cycle](https://github.com/oemof/tespy/blob/dev/tutorial/basics/rankine.py).

TESpy simulation of the steam rankine cycle of the [Andasol II](https://solarpaces.nrel.gov/project/andasol-2)
parabolic trough power plant with the conditions from this
[paper](https://doi.org/10.1016/j.jprocont.2016.01.002).

> Al-Maliki WA, Alobaid F, Kez V, Epple B. Modelling and dynamic simulation of a parabolic trough power plant. Journal of process control. 2016 Mar 1;39:123-38. [https://doi.org/10.1016/j.jprocont.2016.01.002](https://doi.org/10.1016/j.jprocont.2016.01.002)

### Exercise 4: Simulation of a Supercritical CO2 Power Cycle

Simulation of a [supercritical CO2 power cycle](https://sco2symposium.com/papers2018/cycles/052_Paper.pdf).

> Penkuhn M, Tsatsaronis G. Exergoeconomic analyses of different sCO2 cycle configurations. InProceedings of the 6th International Symposium—Supercritical CO2 Power Cycles, Pittsburgh, PA, USA 2018 Mar (pp. 27-29). [https://sco2symposium.com/papers2018/cycles/052_Paper.pdf](https://sco2symposium.com/papers2018/cycles/052_Paper.pdf)

## Installing

### Prerequisites

- [Git](https://git-scm.com/downloads): Optional.
- [Miniconda3](https://docs.anaconda.com/free/miniconda/index.html)
- Choose an option for GUI of Python & Jupyter (suggestions):
  - [Visual Studio Code](https://code.visualstudio.com/) (recommended)
  - [Spyder](https://www.spyder-ide.org/>)
  - [pycharm](https://www.jetbrains.com/pycharm/)
  - or any other GUI for Python
- Install the Jupyter & Python extension for your GUI

### Download the Files

#### Option A: Clone Repository (Git CMD)

1. Open `Git Bash` or `Git GUI`
2. Decide the folder where the files should be stored
3. Navigate with the git command prompt to this folder: `cd 'c:/path/to/folder'`
4. Clone downloaded repository with git: `git clone 'https://github.com/ddceruti/csp-exercises.git'`
5. exit Git

#### Option B: Download .zip

Alternatively, you can download the repository as a .zip from <https://github.com/ddceruti/csp-exercises> and extract the files.
Then, continue from step 3. of Option A.

### Install Required Packages

1. Open the `Anaconda Powershell Prompt`
2. Navigate to the cloned repository and access the csp folder in explorer: `cd 'c:/path/to/folder/csp-exercises'`
3. Create a new environment, name it `csp` and install the latest Python version  `conda create -n csp python=3.11`
4. Activate the environment `conda activate csp` so that all packages and changes are contained within it.
5. Install all required packages `pip install -r requirements.txt` (can take a while to finalize)
6. Check installed packages with command `conda list` (especially check for 'notebook')

## Getting Started

The best way to solve the exercises is to open an 'empty' notebook and try to run all cells.
Then the exercises can be done within each "empty" jupyter notebook file, where the questions can be answered
directly in the empty cells below.
A 'solution' version of the exercise is also uploaded - the students are advised to try first on their own in the 'empty' version.

Here is an example workflow:

1. Open the Anaconda Powershell Prompt
2. Activate environment `conda activate csp`: always switch to this environment, otherwise you can damage the (base) path and you have to re-install all from scratch
3. Launch jupyter-notebook `jupyter notebook`: <https://docs.jupyter.org/en/latest/running.html>
4. Navigate to file and run all cells: <https://saturncloud.io/blog/Jupyter-notebook-run-all-cells-a-comprehensive-guide/>
5. To stop jupyter server press 'ctrl+c' two times in the miniconda3 command prompt

## Documentation on Key Packages

### Jupyter Notebook

<https://docs.jupyter.org/en/latest/>

### pandas

- <https://pandas.pydata.org/pandas-docs/stable/user_guide/index.html#user-guide>
- <https://pandas.pydata.org/docs/user_guide/10min.html#min>
- <https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf>
- <https://pandas.pydata.org/docs/getting_started/tutorials.html#communitytutorials>

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
- Hussein, Hassan (TUM)
- Jundi, Jihad (TUM)
- Tataranni, Urbano (TUM)

## Contribute

Contributions are welcome. Please post an issue or a pull request.

## License

[MIT License](https://en.wikipedia.org/wiki/MIT_License)
