## Local data sources
Local data source files are located in this `.local` directory of this repository. As these include personal data, they are part of `.gitignore` and are to be used and consumed solely for the purposes of data exploration.

- **Apple Health**: data is stored in the `apple-health` directory, and it includes the exported XML file from the Apple Health app.

## Remote data sources
Remote data sources are not stored in this repository, but they can be accessed through APIs or other means. The following are the remote data sources that are currently being used for data exploration:

- **Zepp**: data is located in in a REST API. There are existing projects like [huami-token](https://github.com/agu3rra/huami-token-codeberg/blob/1b32658519d1f35cd3c4345bb9ced3ba6881bb56/huami_token/constants.py#L33-L38), which appear to have reverse engineered the Zepp API thru the means of proxy apps. It's a good starting point for us to not have to start from scratch.

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