# This translates any vowel letter in a word to 'd'.
word = input("name a word: ")
print("your result: ",end="")
for letter in word:
   if letter in "aeiouAEIOU":
      print("d",end="")
   else:
      print(letter,end="")
