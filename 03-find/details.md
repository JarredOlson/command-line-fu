# find
The find utility recursively descends the directory tree for each path listed to find matching files.

## Why is it useful?
Being able to locate a file or directory on a filesystem is extremely useful, especially if you're on a system or server you're not familiar with.

## Basic usage
`find [location] -name [name to match]`

## Example
-`find . -name \*.java -type f` find all of the files with the extension '.java' under the current '.' directory
-`find /tmp -name backup -type d` find all of the directories with the name 'backup' under the '/tmp' directory
