To set up

```
git clone git@github.com:chrisroadmap/wrf-solar.git
cd wrf-solar
conda env create -f environment.yml
conda activate wrf-solar
```

Then create a `.env` file in the top directory of the repository and point `DATADIR` to where the input datafiles are stored

```
# contents of .env
DATADIR=/path/to/datafiles
```
