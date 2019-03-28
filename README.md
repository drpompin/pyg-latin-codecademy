# pyg-latin-codecademy
#In this lesson we'll put together all of the Python skills we've learned so far including string manipulation and branching. #We'll be building a Pyg Latin translator. (That's Pig Latin for Python Programmers!)



pyg = 'ay'

original = raw_input('Enter a word:')

if len(original) > 0 and original.isalpha():
  word = original.lower()
  first = word[0]
  new_word = word + first + pyg
  new_word = new_word[1: ]
  print new_word
else:
  print 'empty'
