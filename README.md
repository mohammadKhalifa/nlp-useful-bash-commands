# :candy: Useful Bash Commands for NLP
A collection of useful bash commands for data manipulation in MLP


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
for file in *; do mv "$file" "arxsum-$file"; done 
```
