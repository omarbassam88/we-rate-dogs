# WeRateDogs Data Wrangling

This project started as an assessment for for the **Udacity Data Analysis Professional Track**.

The dataset is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because:
> ["they're good dogs Brent."](https://knowyourmeme.com/memes/theyre-good-dogs-brent) 

WeRateDogs has over 4 million followers and has received international media coverage.

<center><img width="50%" src ="dog-rates-social.jpg"/></center>

## Challenges

Working with real world data is not a an easy process. Data needed to be gathered from different sources both manually and programmatically. after the data was cleaned, it was stored locally in separted files to appply the analysis and visualization to them.

## Project files

- `wrangle_act.ipynb` : The main process of wrangling, analyzing and visualizing the data.
- `wrangle_report.html` : The final summery of the data wrangling efforts exported from `wrangle_report.ipynb`.
- `act_report.html` : The final data analysis and visualization exported form `wrangle_act.ipynb`.
- `twitter_archive_master.csv` : Cleaned data of from the Twitter archive and Twitter API.
- `image_predictions_clean.csv` : The Cleaned data of the image predictions from the neural network.
- `reportexport.sh` : a bach script to run if re-exporting the HTML files is needed.

## Languages used

- [Python](https://www.python.org) (3.8 or above recommended)

## Requirements

- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [Requests](https://requests.readthedocs.io/en/master/)
- [Tweepy](https://www.tweepy.org/)
- [json](https://docs.python.org/3/library/json.html)
- [re](https://docs.python.org/3/library/re.html)

if you don't have the requirements you can install them using [pip](https://pypi.org/project/pip/):

```Bash
pip install -r requirements.txt
```

if you are using conda use the command below instead:

```Bash
conda env create -f environment.yaml
```

## Recommended Tools

- [VS Code](https://code.visualstudio.com/)
- [Jupyter Notebooks](https://jupyter.org/)
- [Anaconda](https://www.anaconda.com/)

## References

- [Check if file exists in Python](https://www.guru99.com/python-check-if-file-exists.html)
- [Pandas wide_to_long](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.wide_to_long.html)
- [Python Regex](https://www.w3schools.com/python/python_regex.asp)
- [regexr.com](https://regexr.com/)