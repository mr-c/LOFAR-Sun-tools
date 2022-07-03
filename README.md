# LOFAR Sun Tools

 Handy scripts and modules for the LOFAR data processing for Solar and Space Weather.
 Installation guide [docs/install.md](doc/install.md)
 For docker user: [lofarsundocker](https://github.com/Pjer-zhang/lofarsunDocker)

## Data Type

* (.MS) Interferometry raw data, measurement set. [docs/interferometry.md](doc/interferometry.md)
* (.h5) Beamformed data, HDF5 format. [docs/beamformed.md](doc/beamformed.md)
* (xxx-cube.fits) Beamformed data, fits cube.[docs/beamformed.md](doc/beamformed.md)
* (xxx-image.fits) Interferometry image data.[docs/interferometry.md](doc/interferometry.md)

## Install

Go to a empty directory, run the following command.

```bash
git clone https://github.com/peijin94/LOFAR-Sun-tools.git
cd LOFAR-Sun-tools
# (conda activate xxx)
python setup.py install
```

Run quick view for TAB-cube-fits:
```bash
# (conda activate xxx)
lofarBFcube
```
Then load beamformed imaging fits and preview:

![image](./docs/img/image.png)

## Cite as

[https://arxiv.org/abs/2205.00065](https://arxiv.org/abs/2205.00065)