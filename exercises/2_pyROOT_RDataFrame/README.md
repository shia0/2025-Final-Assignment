# PyROOT exercises

Here you find 5 Jupyter Notebooks with pyROOT exercises.
You can run them within any notebook environment as long as pyROOT is available.


## Suggested Setup

Set up a CMSSW Python virtual environment by running the following commands in the LPC

```bash
source /cvmfs/cms.cern.ch/cmsset_default.sh
cmsrel CMSSW_14_1_0_pre3
cd CMSSW_14_1_0_pre3/src
cmsenv
scram-venv
cmsenv
```

Proceed to open Jupyter Lab by running.

```bash
pip3 install jupyterlab
jupyter lab --no-browser --port=8888
```

Navigate to the link that appears in your terminal once it finishes starting up.
