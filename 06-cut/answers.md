### Question 1.
Extract only hour and minutes from the `data/times.txt` file
Answer: `cut -d ':' -f1,2 data/times.txt | cut -d ' ' -f 5`
