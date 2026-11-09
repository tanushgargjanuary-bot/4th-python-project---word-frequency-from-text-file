# Word Frequency from a Text File

A beginner Python program that reads a text file, counts each word, and prints the ten most frequent words.

## Run

Requires Python 3.

The current script contains a Windows file path. Open `Code` and change the path in the `open(...)` call to the location of your own text file.

Then run:

```bash
python Code
```

## How it works

1. Reads the full text file.
2. Splits the text into words.
3. Counts each word with a dictionary.
4. Copies the counts so it can remove words as it finds the largest values.
5. Prints the ten most frequent words and their counts.

## Learning goals

This project practises:
- Reading files
- Dictionaries
- Loops
- Dictionary methods such as `.items()` and `.copy()`
- Finding maximum values
- Building and updating lists

## Limitations

- The input path is currently hard-coded.
- Word matching is case-sensitive.
- Punctuation remains attached to words.
- The script expects enough distinct words for its top-ten loop.
