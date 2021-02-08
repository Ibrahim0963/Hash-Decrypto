import hashlib
import sys
class Myhashing:
    def fun_hash(self, hash_text, hash_type):
        hash_text = hash_text.encode("utf-8")
        h = hashlib.new(hash_type)
        h.update(hash_text)
        word_hashed = h.hexdigest()
        if word_hashed == hashed_text:
            print("congratulation :) , your text has been encrypted !!!!")
            print(hashed_text, " = ", word)
            sys.exit() 
        elif print("trying ", word):
            print("")
        else:
            print("Hashed text not found in this wordlist, try another one !!!!!") # pop just at the end



print("Welcome to my hashing script.......")
print("")

print(hashlib.algorithms_available)
hash_type = str(input("Enter your hash type : "))
while hash_type == "":
    hash_type = print("Please enter your hashed type to hashed : ")


hashed_text = str(input("Enter your hashed text : "))
while hashed_text == "":
    hashed_text = print("Please enter your hashed text to hashed : ")


wordlist = input("Enter you wordlist : ")
while wordlist == "":
    wordlist = print("Please enter your wordlist : ")

wordlistvar = open(wordlist, "r")
for word in wordlistvar.readlines():
    word = word.rstrip("\n")
    myh = Myhashing()
    myh.fun_hash(word, hash_type)
