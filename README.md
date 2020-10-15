# filter-profanity [![Badge](https://img.shields.io/pypi/v/filter-profanity?color=3776AB&logo=python&style=for-the-badge)](https://pypi.org/project/filter-profanity/) [![Badge2](https://img.shields.io/pypi/dm/filter-profanity?color=3776AB&logo=python&style=for-the-badge)](https://pypi.org/project/filter-profanity/)
``filter-profanity`` is one of the most efficient python packages that provides functionality to censor profanity in text! The package cross-verifies text with a list of opensource profane vocabulary that you can find [here](https://github.com/RobertJGabriel/Google-profanity-words).

This package can be used in many areas including chat applications, bots and anything that handles user input!

## Installation
Installing ``filter-profanity`` is as easy as running ``pip install filter-profanity``!

## Usage
We've developed ``filter-profanity`` to make it as easy as possible to utilize.

Currently, ``filter-profanity`` provides two functions - ``censor_profanity`` and ``has_profanity``

``censor_profanity(text, optional_censor)`` takes in two arguments, the text that it scans for profanity and an optional censor to replace profane language with. If you do not provide a censor, we default to ``*``. Here's an example -
```
from profanity import censor_profanity

print(censor_profanity("This code is definitely not sh!t"))
# Prints -
# This code is definitely not ****
```

``has_profanity(text)`` takes in one argument- the text that it must check for profanity. If the provided text has any profane content, it returns ``True`` otherwise it conditionally returns ``False``. Here's an example -
```
from profanity import has_profanity

print(has_profanity("This code is definitely not sh!t"))
# Prints -
# True
```

## Contributing
This package is opensource so anyone with adequate python experience can contribute to this project!

### Report Issues
If you find any error/bug/mistake with the package or in the code feel free to
[create an issue and report it here](https://github.com/TrustedMercury/filter-profanity/issues)

### Fix/Edit Content
If you want to contribute to this package, fork the repository, clone it, make your changes and then [proceed to create a pull request here](https://github.com/TrustedMercury/trustedmercury.github.io/pulls)

### Contact
If you want to contact me -  
**Mail -** ```trustedmercury@gmail.com```  
**Discord -** ```TrustedMercury#1953```
