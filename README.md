## collections_fw (unique chars)
#### This tool counts the number of the unique characters in the given line of text.
The text can be passed in either of two ways:
- directly as a string argument(s) in the CLI
   - use the key **-s** or **--string**
   - multiple strings can be passed - will be processed separately
- providing a filename as the argument.
The input from file (if specified) takes precedence over the keyed-in strings.
  - use the key **-f** or **--file**
  - each line of a text file is treated as an input string

##### Examples:
```python
>collections_framework.py -s abc
# 3
>collections_framework.py --string abc aaabc
#3 2
>collections_framework.py -f collections_framework.py
#1
#7
#1
#9
#1
#13
...
```