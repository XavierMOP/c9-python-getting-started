# Getting started with Python

## Overview

The series of videos on Channel 9 is designed to help get you up to speed on Python. If you're a beginning developer who's looking to add Python to your quiver of languages, or trying to get started on a data science or web project, these videos can help teach you the foundation necessary to walk through a quick start or other tutorial.

### What you'll learn

- The basics of Python
- Starting a project
- Common syntax
- Package management

### What we don't cover

- Class design and inheritance
- Asynchronous programming
- Basics of programming

## Prerequisites

- [An understanding of Git](https://git-scm.com/book/en/v1/Getting-Started)
- Light experience with another programming language, such as [JavaScript](https://www.edx.org/course/javascript-introduction)

## Next steps

As the goal of this course is to help get you up to speed on Python so you can work through a quick start, the next step after completing the videos is to follow a tutorial! Here's a few of our favorites:

- [Quickstart: Detect faces in an image using the Face REST API and Python](https://docs.microsoft.com/en-us/azure/cognitive-services/face/QuickStarts/Python?WT.mc_id=python-c9-niner)
- [Quickstart: Analyze a local image using the Computer Vision REST API and Python](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/quickstarts/python-disk?WT.mc_id=python-c9-niner)
- [Quickstart: Using the Python REST API to call the Text Analytics Cognitive Service](https://docs.microsoft.com/en-us/azure/cognitive-services/Text-Analytics/quickstarts/python?WT.mc_id=python-c9-niner)
- [Tutorial: Build a Flask app with Azure Cognitive Services](https://docs.microsoft.com/en-us/azure/cognitive-services/translator/tutorial-build-flask-app-translation-synthesis)
- [Flask tutorial in Visual Studio Code](https://code.visualstudio.com/docs/python/tutorial-flask?WT.mc_id=python-c9-niner)
- [Django tutorial in Visual Studio Code](https://code.visualstudio.com/docs/python/tutorial-django?WT.mc_id=python-c9-niner)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

# print

The print function allows you to send output to the terminal

- [print](https://docs.python.org/3/library/functions.html#print)

Strings can be enclosed in single quotes or double quotes

- "this is a string"
- 'this is also a string'

The input function allows you to prompt a user for a value

- [input](https://docs.python.org/3/library/functions.html#input)

Parameters:

- `prompt`: Message to display to the user

return value:

- string value containing value entered by user
# Comments

Comments start with a hash character (#) and allow you to document your code.
Comments are ignored when code is executed.

- [Comments](https://docs.python.org/3/reference/lexical_analysis.html?highlight=comment)
# Strings

Python can store and manipulate strings. Strings can be enclosed in single or double quotes. There are a number of string methods you can use to manipulate and work with strings

- [strings](https://docs.python.org/3/tutorial/introduction.html#strings)
- [string methods](https://docs.python.org/3/library/stdtypes.html#string-methods)

Converting to string values

- [str](https://docs.python.org/3/library/functions.html#func-str)

When naming variables follow the PEP-8 Style Guide for Python Code

- [PEP-8 Style Guide](https://www.python.org/dev/peps/pep-0008/#naming-conventions)
# Numeric values

Python can store and manipulate numbers. Python has two types of numeric values: integers (whole numbers) or float (numbers with decimal places)

- [numeric types](https://docs.python.org/3/library/stdtypes.html#numeric-types-int-float-complex)

When naming variables follow the PEP-8 Style Guide for Python Code

- [PEP-8 Style Guide](https://www.python.org/dev/peps/pep-0008/#naming-conventions)

Converting to numeric values

- [int](https://docs.python.org/3/library/functions.html#int)
- [float](https://docs.python.org/3/library/functions.html#float)
# Date values

The [datetime module](https://docs.python.org/3/library/datetime.html) contains a number of classes for manipulating dates and times.

Date and time types:

- `date` stores year, month, and day
- `time` stores hour, minute, and second
- `datetime` stores year, month, day, hour, minute, and second
- `timedelta` a duration of time between two dates, times, or datetimes

When naming variables follow the PEP-8 Style Guide for Python Code

- [PEP-8 Style Guide](https://www.python.org/dev/peps/pep-0008/#naming-conventions)

Converting from string to datetime

- [strptime](https://docs.python.org/2/library/datetime.html#strftime-and-strptime-behavior)
# Error handling

Error handling in Python is managed through the use of [try/except/finally](https://docs.python.org/3.7/reference/compound_stmts.html#except)

Python has numerous [built-in exceptions](https://docs.python.org/3.7/library/exceptions.html). When creating `except` blocks, they need to be created from most specific to most generic according to the [hierarchy](https://docs.python.org/3.7/library/exceptions.html#exception-hierarchy).
# Handling conditions

Conditional execution can be completed using the [if](https://docs.python.org/3/reference/compound_stmts.html#the-if-statement) statement

`if` syntax

```python
if expression:
    # code to execute
else:
    # code to execute
```

[Comparison operators](https://docs.python.org/3/library/stdtypes.html#comparisons)

- < less than
- < greater than
- == is equal to
- \>= greater than or equal to
- <= less than or equal to
- != not equal to
# Handling conditions

Conditional execution can be completed using the [if](https://docs.python.org/3/reference/compound_stmts.html#the-if-statement) statement. Adding `elif` allows you to check multiple conditions

`if` syntax

```python
if expression:
    # code to execute
elif expression:
    # code to execute
else:
    # code to execute
```

[Boolean operators](https://docs.python.org/3/library/stdtypes.html#boolean-operations-and-or-not)

- **x *or* y** - If either x OR y is true, the expression is executed

[Comparison operators](https://docs.python.org/3/library/stdtypes.html#comparisons)

- < less than
- < greater than
- == is equal to
- \>= greater than or equal to
- <= less than or equal to
- != not equal to
- **x *in* [a,b,c]** Does x match the value of a, b, or c
# Complex condition checks

Conditional execution can be completed using the [if](https://docs.python.org/3/reference/compound_stmts.html#the-if-statement) statement.

`if` syntax

```python
if expression:
    # code to execute
elif expression:
    # code to execute
else:
    # code to execute
```

[Boolean values](https://docs.python.org/3/library/stdtypes.html#boolean-values) can be either `False` or `True`

[Boolean operators](https://docs.python.org/3/library/stdtypes.html#boolean-operations-and-or-not)

- **x *or* y** - If either x **OR** y is true, the expression is executed
- **x *and* y** - If x **AND** y are both true, the expression is executed

[Comparison operators](https://docs.python.org/3/library/stdtypes.html#comparisons)

- < less than
- < greater than
- == is equal to
- \>= greater than or equal to
- <= less than or equal to
- != not equal to
- **x *in* [a,b,c]** Does x match the value of a, b, or c
# Collections

Collections are groups of items. Python supports several types of collections. Three of the most common are dictionaries, lists and arrays.

## Lists

[Lists](https://docs.python.org/3/tutorial/introduction.html#lists) are a collection of items. Lists can be expanded or contracted as needed, and can contain any data type. Lists are most commonly used to store a single column collection of information, however it is possible to [nest lists](https://docs.python.org/3/tutorial/datastructures.html#nested-list-comprehensions)
## Arrays

[Arrays](https://docs.python.org/3/library/array.html) are similar to lists, however are designed to store a uniform basic data type, such as integers or floating point numbers.

## Dictionaries

[Dictionaries](https://docs.python.org/3/tutorial/datastructures.html#dictionaries) are key/value pairs of a collection of items. Unlike a list where items can only be accessed by their index or value, dictionaries use keys to identify each item.
# Loops

## For loops

[For loops](https://docs.python.org/3/reference/compound_stmts.html#the-for-statement) takes each item in an array or collection in order, and assigns it to the variable you define.

``` python
names = ['Christopher', 'Susan']
for name in names:
    print(name)
```

## While loops

[While loops](https://docs.python.org/3/reference/compound_stmts.html#the-while-statement) perform an operation as long as a condition is true.

``` python
names = ['Christopher', 'Susan']
index = 0
while index < len(names):
    name = names[index]
    print(name)
    index = index + 1
```
# Functions

Functions allow you to take code that is repeated and move it to a module that can be called when needed. Functions are defined with the `def` keyword and must be declared before the function is called in your code. Functions can accept parameters and return values.

- [Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)

```python
def functionname(parameter):
    # code to execute
    return value
```
# Function parameters

Functions allow you to take code that is repeated and move it to a module that can be called when needed. Functions are defined with the `def` keyword and must be declared before the function is called in your code. Functions can accept one or more parameters and return values.

- [Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)

```python
def function_name(parameter):
    # code to execute
    return value
```

Parameters can be assigned a [default value](https://docs.python.org/3/tutorial/controlflow.html#default-argument-values) making them optional when the function is called.

```python
def function_name(parameter=default):
    # code to execute
    return value
```

When you call a function you may specify the values for the parameters using positional or [named notation](https://docs.python.org/3/tutorial/controlflow.html#keyword-arguments)

```python
def function_name(parameter1, parameter2):
    # code to execute
    return value

# Positional notation pass in arguments in same order as parameters are declared
result = function_name(value1,value2)

# Named notation
result = function_name(parameter1=value1, parameter2=value2)
```
# Packages and modules

## Modules

[Modules](https://docs.python.org/3/tutorial/modules.html) allow you to store reusable blocks of code, such as functions, in separate files. They're referenced by using the `import` statement.

``` python
# import module as namespace
import helpers
helpers.display('Not a warning')

# import all into current namespace
from helpers import *
display('Not a warning')

# import specific items into current namespace
from helpers import display
display('Not a warning')
```

## Packages

[Distribution packages](https://packaging.python.org/glossary/#term-distribution-package) are external archive files which contain resources such as classes and functions. Most every application you create will make use of one or more packages. Imports from packages follow the same syntax as modules you've created. The [Python Package index](https://pypi.org/) contains a full list of packages you can install using [pip](https://pip.pypa.io/en/stable/).

## Virtual environments

[Virtual environments](https://docs.python.org/3.7/library/exceptions.html) allow you to install packages into an isolated folder. This allows you to better manage versions.

``` console

```
# Calling APIs

You can call functions called by other programs hosted on web servers.
[Microsoft Azure Cognitive Services](https://docs.microsoft.com/en-ca/azure/cognitive-services/) contain a number of APIs you can call from your code to add intelligence to your apps and websites.

In the code example you call the [Analyze Image](https://westus.dev.cognitive.microsoft.com/docs/services/5adf991815e1060e6355ad44/operations/56f91f2e778daf14a499e1fa) function of the [Computer Vision](https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/)

Calling the API requires
- [API Key](https://azure.microsoft.com/en-ca/try/cognitive-services/) to give you permission to call the API
- Address or Endpoint of the service
- function name of method to call as listed in the [API documentation](https://westus.dev.cognitive.microsoft.com/docs/services/5adf991815e1060e6355ad44/operations/56f91f2e778daf14a499e1fa)
- function parameters as listed in the [API documentation](https://westus.dev.cognitive.microsoft.com/docs/services/5adf991815e1060e6355ad44/operations/56f91f2e778daf14a499e1fa)
- HTTP Headers as listed in the [API documentation](https://westus.dev.cognitive.microsoft.com/docs/services/5adf991815e1060e6355ad44/operations/56f91f2e778daf14a499e1fa)

# JSON

Many APIs return data in [JSON](https://json.org/), JavaScript Object Notation. JSON is a standard format that can is readable by humans and parsed or generated by code.

JSON is built on two structures:
- collections of key/value pairs
- lists of values

JSON Linters will format JSON so it easier to read by a human. The following website have JSON linters:
- [JSONLint](https://jsonlint.com/)
- [ConvertJson.com](http://www.convertjson.com/jsonlint.htm)
- [JSON schema linter](https://www.json-schema-linter.com/)

Python includes a [json](https://docs.python.org/2/library/json.html) module which helps you encode and decode JSON
# Decorators

[Decorators](https://www.python.org/dev/peps/pep-0318/) are similar to attributes in that they add meaning or functionality to blocks of code in Python. They're frequently used in frameworks such as [Flask](http://flask.pocoo.org/) or [Django](https://www.djangoproject.com/). The most common interaction you'll have with decorators as a Python developer is through using them rather than creating them.

``` python
# Example decorator
@log(True)
def sample_function():
    print('this is a sample function')
```
