### Question 1.
In the `data/` directory find all of the pom.xml files.
Answer: There are 3 pom.xml files.  `find data/ -name pom.xml`

### Question 2.
In the `data/` directory find all of the .java files.
Answer: There are 3 java files. `find data/ -name \*.java -type f`

### Question 3.
In the `data/` directory find all of the empty files.
Answer: There are 2 empty files `find data/ -size 0`

### Question 4.
In the `data/` directory find and remove all of the `.DS_Store` files.
Answer: `find . -name \.DS_Store -exec rm {} \;`

### Question 5.
In the `data/` directory find all of the defined spring dependencies in a pom file.
find . -name pom.xml -exec grep -i -C 2 'spring' {} \;
