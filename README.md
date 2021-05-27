# Autolist

Python Basic Library for Auto-Correct purposes using lists.

## How to Use Autolist ?
Type the below command in your windows terminal :

`pip install autolist` OR [Click this link](https://pypi.org/project/autolist/)

If the above didn't work, check the following :
- [Python3](https://www.python.org/) is working and is updated to the latest version
- [Pip](https://pypi.org/project/pip/) is updated to the latest version

## Examples
```python
# Import the Module
import autolist as al

# Create a list which has all the correct words OR Take input from user
correct_words_list = ["autolist","advanced","listing"]
string = "autosift" # Take input from user or Give a String

# Autolist checks the list and corrects it using the following
print(al.autocorrect_list(string, correct_words_list))
```

## Application
1. Discord Bots :
  Where the words are auto-corrected using the given correct words list. This will help make the bot more easier and better.
2. Python Programs :
  Where you take input from user for a definite options but you fear that user will mistype. Autolist autochecks and corrects the mistyped word.

## Features
- Autocorrect words into the most similiar word specified in a given list

## Suggestions
We are ready to accept your suggestions.
Contact via :
- Message me on Discord (AbelR007#5096)
- Create an Issue in [Autolist Github](https://github.com/AbelR007/Autolist)
