## Local data sources
Local data source files are located in this `.local` directory of this repository. As these include personal data, they are part of `.gitignore` and are to be used and consumed solely for the purposes of data exploration.

- Apple Health data is stored in the `apple-health` directory, and it includes the exported XML file from the Apple Health app.

## Data exploration and analysis
To facilitate the exploration and analysis of the data, you can use the Jupyter notebooks located in the `data-exploration` directory.
Inside this same directory you'll find Python's UV dependency manager files. To activate the virtual environment, run:

```bash
# install the dependencies
uv sync
source .venv/bin/activate
```

Once the virtual environment is activated, you can run `python3` commands simply calling it `python`.

Jupyter notebooks are to be created in the `data-exploration/notebooks` directory, and they can be run using the following command:

```bash
# launches the jupyterlab server
jupyterlab
# or simply open the notebook in VScode and run the cells there
```