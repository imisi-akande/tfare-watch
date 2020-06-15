# tfare-watch
This project contains wrangling of the [`transport fare dataset`](https://www.nigerianstat.gov.ng/elibrary?page=3&offset=20) in Nigeria
from the year January 2016 to March 2020. 
The dataset contains average transport fare per month for five means of transportation: air, intercity, intracity, motorcycle and water.
The mean of all transport fare routes per year was obtained from the existing average transport fare per month and read into CSV files.

## Instructions
- Enter your terminal:
    -  Clone the repository:
         - ```https://github.com/imisi-akande/tfare-watch.git```

- Change Directory into tfare-watch:
    - ```cd tfare-watch```

- Create a virtual environment:
    - ```python -m venv tfare-env```

- Activate the environment:
    - ```source tfare-env/bin/activate```

- Install the packages:
    - ```pip install -r requirements.txt```

- Add your virtual environment to Jupyter:
    - ```python -m ipykernel install --user --name=tfare-env```

- Start notebook:
    - ```jupyter notebook```

- Project composition:
- [`InitialDataWrangling.ipynb:`](https://github.com/imisi-akande/tfare-watch/blob/develop/InitialDataWrangling.ipynb)
The interactive environment that displays the step by step wrangling of the transport fare dataset and exports all resulting dataframes as CSV files

- [`data:`](https://github.com/imisi-akande/tfare-watch/tree/develop/data)
The folder that embeds the resulting CSV files which in turn contains the mean of all transport fare routes per year. This files are five in number.

