### Question 1. In the `data/people/people.csv` file how many people have 'Smith' as part of their name?
Answer. 2 people have the name 'Smith'. `grep 'Smith' data/people/people.csv`.  The basic useage of grep is `grep '[pattern]' [file or directory]`

### Question 2. In the `data/people/people.csv` file how many people don't have 'Smith' as part of their name?
Answer. 3 people don't have the name 'Smith'. `grep -v 'Smith' data/people/people.csv`  -v returns everything that does not match the given pattern.

### Question 3. In the `data/people/` directory how many people have 'Smith' as part of their name?
Answer. 3 people have the name 'Smith' in the whole `data/people` directory.  `grep -r 'Smith' data/people/`.  -r makes the search recursive for the given directory.

### Question 4. In the `data/maven_project/` what version of spring is being used?
Answer. 4.2.1.RELEASE. `grep -C 1 'spring' data/maven_project/pom.xml`  `-C #` will give us the given number of lines before and after a given match.  Similarly `-A #` can be used to give context after a given match and `-B #` can be used to give context before a given match.
