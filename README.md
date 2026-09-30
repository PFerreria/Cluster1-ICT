# Cluster 1: Attentional cost of smartphone notification

## How to prepare computer for Experiment:

1. Create virtual environment to maintain reproducibility:
- Needs Python 3.11 or 3.12, but can be tested with any Python version
- `python -m venv venv`
- Access venv: `.\venv\Scripts\activate`

2. Download Android Debug Bridge (adb)
   - Link to download: https://developer.android.com/tools/adb
   - Add the location (file path) to `phone_control.ipynb`, section "Settings": Substitute ADB_PATH = r"C:\Users\xxxxxxxx\platform-tools\adb.exe" with your path.

3. Install `psychopy`: `pip install psychopy`
- If there is any problem with missing `swig.exe`, download here: https://sourceforge.net/projects/swig/files/swigwin/swigwin-4.4.1/
    - Extract the .zip
    - Add to PATH the extracted zip folder file
 
4. Environment settings
   - In "Settings", set Simulate = TRUE to FALSE
   - In the experiment, add the phone number of the participants in `participants.csv`
   - Do not edit any of the other files. If they were edited, recover the files in the GitHub
