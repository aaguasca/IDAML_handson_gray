Hands-on session of IDAML about the analysis of very-high-energy gamma-ray sources using Gammapy

## Install

- You will need to install [miniconda](https://docs.conda.io/en/latest/miniconda.html) (recommended) or [anaconda](https://www.anaconda.com/distribution/#download-section) first. 

- Clone the repository
```bash
git clone https://github.com/aaguasca/IDAML_gray_handson.git
cd IDAML_gray_handson
```
Or download it without git as follows: On the main page of the repository, in the top right of the webpage, press CODE (green button) and click the "Download ZIP" option at the bottom of the pop-up options. Move the zip file to the desired location and decompress it. Open a terminal and `cd` to the IDAML_gray_handson directory. 

- Create and activate the gammapy v2.1 environment
If you use Windows, use (once inside the IDAML_gray_handson directory):
```bash
conda env create -f gammapy-2.1-environment-windows.yml
conda activate gammapy-2.1
```
Else,
```bash
conda env create -f gammapy-2.1-environment.yml
conda activate gammapy-2.1
```

## Repository structure

- `hess-dl3-dr1/`: Input data.
- `images/`: Images used in the Jupyter Notebooks.
- `joint-crab/`: Files used in the Jupyter Notebooks.
- `high_level_interface_3D.py`: 3D analysis fitting using the high-level interface.
- `introduction_data_format.py`: Explanation of standard IACT data format.

## Usage

1. **Activate Environment**:
   ```bash
   conda activate gammapy-2.1
   ```

2. **Launch Jupyter**:
   ```bash
   jupyter notebook
   ```

3. **Open the Jupyter Notebooks**:
   - `introduction_data_format.py`
   - `high_level_interface_3D.py`
