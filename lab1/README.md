# Firs Lab - Words Counter
## Files `*.java`
- `Main.java` - create classes to handle input and outpur files;
- `Collector.java` - read input file and collect info: number of words and map (format: word, word number)
- `Writer.java` - sort map by number of words in descending order and write this information in file (`.csv` format: word;frequency;percents)
## Compiling and running
To compile use next command
```cmd
javac *.java
```

To run use
```cmd
java Main in.txt out.csv
```

## Information about the input files
- File `tmp.txt` includes **"Crusoe"**
- File `in.txt` includes **some suspicious character combinations**
