# :candy: useful bash commands for Natural Language Processing :candy:
*A collection of useful bash commands that I use a lot for data manipulation, wrangling, and preprocessing in NLP*


* *split tsv file, and extract 3rd and 5th columns*
```
cut -f3,5 -d'      ' filename.tsv
```

* *Remove first line from file*
```
tail -n +2 filename.txt
```

* *Oneliner add a prefix to the names of all files inside a folder*
```
for file in *; do mv "$file" "prefix-$file"; done 
```
