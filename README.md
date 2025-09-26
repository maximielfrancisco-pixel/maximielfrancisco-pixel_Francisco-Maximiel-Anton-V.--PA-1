# maximielfrancisco-pixel_Francisco-Maximiel-Anton-V.--PA-1
------
### 1) Alphabet Soup Problem - Creates a function that organizes the letters of a word in ascending alphabetical order (A to Z).
```python

 # FUNCTION TO SORT
def alphabet_soup(w):
    return ''.join(sorted(w))

# INPUT ANY WORD TO SORT
word = input("ENTER A WORD: ")

print("SORTED WORD:", alphabet_soup(word))

```
##### Step-by-Step Procedure of Functions:
- `def alphabet_soup(w)` → combines the sorted list of characters back into a single string.
- `sorted(w)` → arranges the characters of the input word in alphabetical order.
- `''.join()` → combines the sorted list of characters back into a single string.
- `''.join(sorted(w))` → joins the sorted letters back into a single string.
- `input()` → lets the user type in a word for the program to process.
- `print("SORTED WORD:", alphabet_soup(word))` → displays the sorted version of the word.

------
### 2) Emoticon Problem - Creates a function that converts certain words into their corresponding emoticons.

```python
  # WORDS INTO EMOTIONS
def emotify(phrases):
    # WORDS TO EMOJIS
    emoticons = {
        "smile": ":)",
        "grin": ":D",
        "sad": ":((",
        "mad": ">:("
    }

    # FUNCTION TO REPLACE WORDS TO EMOJIS
    for word, symbol in emoticons.items():
        phrases = phrases.replace(word, symbol)

    return phrases

sentence = input("ENTER A SENTENCE: ")
print("CONVERTED EMOJI:", emotify(sentence))
```
##### Step-by-Step Procedure of Functions:
- `emotify(phrases)` → Functions that takes a sentence as input.
- `emoticons = {}` → defines a dictionary that maps words to their corresponding emojis. Within the code a dictionary emoticons stores the mapping between words ("smile", "grin", etc.) and their emoji equivalents (":)", ":D", "((", ">:( ").
  
- `for word, symbol in emoticons.items()` → loops through each word–emoji pair in the dictionary.
- `phrases.replace(word, symbol)` → replaces every occurrence of the word in the sentence with its emoji.
- `input()` → takes a sentence from the user for conversion.
------
### 3) Unpacking List Problem - Creates a function that splits a user’s input list into three parts: the first item, the middle items, and the last item.

```python
# LIST TO SEPARATE
user_input = input("ENTER LIST : ")

# ARRANGE NUMBERS
lst = user_input.split()

# 3 WAYS SEPARATION
if len(lst) >= 2:
    first, *middle, last = lst
    print("First: ", first)
    print("Middle: ", middle)
    print("Last: ", last)
else:
    print("INPUT MINIMUM OF TWO NUMBERS :>")

```
##### Step-by-Step Procedure of Functions:
- `user_input = input()` → lets the user type a list of numbers or words.
- `user_input.split()` → breaks the input into a list of items separated by spaces.
- `first, *middle, last = lst` → assigns the first item to first, the last item to last, and everything in between to middle.
- `if len(lst) >= 2:` → checks if the list has at least two elements before separating it.

Outcome:
```python
# If the user enters:
10 20 30 40 50

# The program outputs:
First:  10
Middle:  ['20', '30', '40']
Last:  50
```
------

#PA VERSION 2
