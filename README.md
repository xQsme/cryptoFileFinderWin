# cryptoFileFinderWin

Windows version (Linux version at https://github.com/xQsme/cryptoFileFinder)

```
git clone https://github.com/xQsme/cryptoFileFinderWin.git
cd cryptoFileFinder/release
./cryptoFinder
```

Usage:
```
-f   --file                    Single file to analyze
-d   --dir      --directory   Directory to search ("~" by default)
-s   --search                 Search for encrypted files
-o   --output                 Output file ("output.txt" by default)
-t   --test     --testing     Generate csv test data (statistical values for every file)
```

Common Usage:
```
./cryptoFinder -d targetDirectory -o outputFile.csv -s -t
./cryptoFinder -f fileToAnalyze
```
