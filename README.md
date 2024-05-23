# Coding standards

In this repo we will develop our guidelines towards writing code & using repositories.

Driving principles:
- keep things low touch
- focus on productivity and being practical over being formal
- differentiate between different use cases. Multiple use cases might apply to your work

We are building these publicly so other organizations can contribute or adopt what we have done if interested.
Our main use cases at the time of writing are convenience tools to make the org more efficient, data exploratory work with occasional focus on social media.

# Updates and to do
- 23 May 2024: created repo, keeping everything in readme for now. Might move to something nicer later.

# Standards

## Where to keep code

Generally speaking, we consider good pracrtice to have code live in repository or a code snippet. Whether it's a one-off work or a big project.


## When creating any a repo

Make sure to:

- think if it needs to be private or ok to be public
- who else might want to use the repo and what for (the answer could well be nobody ever)
- a readme file listing:
  - what is contained in the repo and what it can be used for
  - intended audience
  - how to use the repo, ideally with detailed steps if needed

- if writing code, make sure not to include any credentials
- flat data files should not live in a repo

## When creating non-production Python projects 

We take inspiration by [PEP 8](https://peps.python.org/pep-0008/#introduction), but keep it low touch.

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

