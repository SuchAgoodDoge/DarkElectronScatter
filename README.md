# DarkElectronScatter
Analysis of the Monte Carlo Generated Data for Dark Matter - Electron Scattering at MicroBooNE

# Run
In folder DarkElectronScatter:
```
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requiremnets.txt
$ python notebooks/generate_data.py "dt_ratio" "number of files" "scalar/fermion" # replace the parameters as appropriate
```

# Noether
To run this on noether:
```
$ cd ~
$ mkdir repo/pure
$ cd repo/pure
$ git clone {DarkTridentGen}
$ cd DarkTridentGen
$ git swtich ElectronScatter
$ cd ~/repo
$ git clone {DarkElectronScatter}
$ cd DarkElectronScatter/condor
$ source jobsub.sh
```
