# cut
Cut out selected portions of each line of a file or input

## Why is it useful?
Sometimes data isn't in the format that we need it to be.  Cut can help us get the data we want in the format we need.

## Basic usage
`cut -d [delimiter] -f [column] [file]`

## Example
`cut -d ' ' -f 1 names.txt` Returns the first column of data separated by the delimiter ' ' in the file names.txt
