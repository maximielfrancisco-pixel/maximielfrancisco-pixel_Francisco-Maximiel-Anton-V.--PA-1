# maximielfrancisco-pixel_Francisco-Maximiel-Anton-V.--PA-1
#### 1) Alphabet Soup Problem - Creates a function that organizes the letters of a word in ascending alphabetical order (A to Z).
- `''.join()` → combines the sorted list of characters back into a single string.
- `sorted()` → arranges the characters of the input word in alphabetical order.
- `input()` → lets the user type in a word for the program to process.

#### 2) Emoticon Problem - Creates a function that converts certain words into their corresponding emoticons.
- `emoticons = {}` → defines a dictionary that maps words to their corresponding emojis.
- `for word, symbol in emoticons.items()` → loops through each word–emoji pair in the dictionary.
- `phrases.replace(word, symbol)` → replaces every occurrence of the word in the sentence with its emoji.
- `input()` → takes a sentence from the user for conversion.

#### 3) Unpacking List Problem - Creates a function that splits a user’s input list into three parts: the first item, the middle items, and the last item.
- `user_input = input()` → lets the user type a list of numbers or words.
- `user_input.split()` → breaks the input into a list of items separated by spaces.
- `first, *middle, last = lst` → assigns the first item to first, the last item to last, and everything in between to middle.
- `if len(lst) >= 2:` → checks if the list has at least two elements before separating it.


