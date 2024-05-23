# Coding standards

In this repo we will develop our guidelines towards writing code & using repositories.

Driving principles:
- keep things low touch
- focus on productivity and being practical over being formal
- differentiate between different use cases. Exploratory work does not perfectly formatted and unit tested code, production work maybe does, maybe does not.

We are building these publicly so others can contribute or adopt what we have done if interested.

# Updates and to do
- 23 May 2024: created repo, keeping everything in readme for now. Might move to something nicer later.

# Use case: non-production Python projects 

We are looking to be inspired by [PEP 8](https://peps.python.org/pep-0008/#introduction), but keep it low touch.

Proposed standards and principles:

- **readability** and **re-usability** are key

- **indentation**: don't go wild, no need to enforce hard standards

- **imports** matter. One import per line, at the beginning of the file ([entirely as per PEP-8](https://peps.python.org/pep-0008/#imports))

- write **doc strings** for all the functions, using triple quote. No need to spell out all what all the parameters do in details. But be clear in what the function does, and how the params come into play

- **naming conventions**: 
  - all lower case. 
  - use informative but concise names for functions and variables. 
  - Use '_' to create clear a *variable_name*
  - be mindful of potential reserved word and tweak variable names. E.g. use 'my_item' instead of 'item'

