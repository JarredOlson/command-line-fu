# uniq aka unique
Filters out repeated lines in a file or input

## Why is it useful?
When looking for duplicates or generating a unique list without duplicates.

## Basic usage
`uniq [file]`

## Example
`sort names.txt | uniq` Returns the unique entries in the names.txt file

`sort names.txt | uniq -c` Returns the unique entries in the names.txt file proceeded by the number of times each entry occurred.
