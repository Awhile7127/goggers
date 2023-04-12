# goggers


## Description

Simple command-line utility to fetch discounted games from
[gog.com](http://www.gog.com), using their [API](https://gogapidocs.readthedocs.io/en/latest/).

Written in Python.


## Usage

```
./src/main <page_limit> <entry_limit> <verbose> <output>
```

- page_limit **REQUIRED**: The number of pages to iterate through
- entry_limit **REQUIRED**: The number of games per page of results
- verbose **OPTIONAL**: Print what's going on to the console
- output **OPTIONAL**: Output games to a file, instead of stdout
