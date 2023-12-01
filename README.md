## Building a Data Analysis pipeline tutorial
adapted from [Software Carpentry](http://software-carpentry.org/)

This example data analysis project analyzes the word count for all words in 4
novels. It reports the top 10 most occurring words in each book in a [report](doc/count_report.Rmd).

### Current usage:

1. Clone this repo, and using the command line, navigate to the root of this project.

2. Run the following commands:

```
bash runall.sh
```

### Exercise:

Your task is to add a "smarter" data analysis pipeline using GNU Make!
It should accomplish the same task as `bash runall.sh` when you type
`make all`.

It should reset the analysis the starting point 
(the state when you first copied this repo)
when you type `make clean`.

### Depenedencies
- Python & Python libraries:
    - `matplotlib`
    - `numpy`
    - `sys`
    - `click`
    - `collections`
    - `wordcount`
    - `jupyter`
    - `jupyter book`
