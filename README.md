# whodunnit
Nice work, Python gumshoe, you found a clue! 

Before you begin, follow the instructions in the `Setup` section below, so you can run the code on your local machine.

## Instructions:
- The `faker_df.py` file imports the dictionary `faker_for_df`. Read this dictionary into a [Pandas DataFrame](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html).
- Find the row in the DataFrame where the country is Canada and the year is between 1970 and 1980.
>The built-in `.query()` method is a good tool for this.
- The value in the '2nd_clue' column of this row will complete your next clue:

_"The website revealing the final clue can be found in the 'address' column of the row where..."_

### Setup
- Clone this repository on to your local computer:

`git clone https://github.com/alma-frankenstein/whodunnit.git`

- Create a Python virtual environment:

`python3.7 -m venv venv`

- Activate it:

`source venv/bin/activate`

- Install the requirements in the `requirements.txt` file:

`pip install -r requirements.txt`

### More Info:
Copyright Data Stack Academy, 2022. [https://www.datastack.academy/](https://www.datastack.academy/)

The treat values were generated using [Cupcake Ipsum](http://www.cupcakeipsum.com/), and other values were generated with Python's wonderful [Faker package](https://faker.readthedocs.io/en/master/index.html).