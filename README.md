# wrangle_in_py

A package for wrangling and tidy data in python. This package includes functions to assist the user with common data wrangling and tidying tasks in python such as changing column names or removing duplicate rows. 

This package consists of the following functions:
- `column_standardizer`: returns a copy of the inputted dataframe with standardized column names.
- `string_standardizer`: returns a string that is converted to lowercase and its non-alphanumerics (including spaces and punctuation) are replaced with underscores.
- `resulting_duplicates`: identifies which strings became duplicates after standardization.
- `extracting_ymd`: returns a copy of the inputted dataframe with three new columns: year, month, and day, splitting from inputted datetime column name.
- `extracting_hms`: returns a copy of the inputted dataframe with three new columns: hour, minute, and second, from inputted datetime column name.
- `remove_duplicates`: removes duplicate rows from a dataframe based on specified columns.
- `column_drop_threshold` : returns a copy of the dataframe inputted with columns removed if they did not meet the threshold specified, 
    or if they had lower variance than specified.

This package fills a niche in the Python ecosystem by offering specialized tools for tidying and wrangling data, focusing on standardizing column names and strings, detecting duplicates after standardization, and extracting components from datetime columns. While libraries like [pandas](https://pypi.org/project/pandas/) provide general-purpose methods for similar tasks, such as renaming columns or working with datetime data, these often require multiple steps or custom scripts. By combining these focused functionalities into a single package, it offers a lightweight, user-friendly alternative for efficient data preprocessing.


## Installation

```bash
$ pip install wrangle_in_py
```

## Usage

- TODO

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`wrangle_in_py` was created by Shannon Pflueger, Stephanie Ta, Wai Ming Wong, Yixuan(Clara) Gao. It is licensed under the terms of the MIT license.

## Credits

`wrangle_in_py` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).

## Contributors
- Shannon Pflueger
- Stephanie Ta
- Wai Ming Wong
- Yixuan(Clara) Gao
