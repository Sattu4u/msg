# msg
Sweety
alphabet = [‘a’, ‘b’, ‘c’, ‘d’, ‘e’, ‘f’, ‘g’, ‘h’, ‘i’, ‘j’, ‘k’, ‘l’, ‘m’, ‘n’, ‘o’, ‘p’, ‘q’, ‘r’, ‘s’, ‘t’, ‘u’, ‘v’, ‘w’, ‘x’, ‘y’, ‘z’]
def encrypt(plaintext, secret_key):
ciphertext=""
for character in plaintext:
if character.isalpha():
character character.lower()
char_index = alphabet.index(character)
new_index = (char_index + secret_key) % 26
cipher_char = alphabet [new_index].upper()
else:
Cipher_char=character
cipher_char character =ciphertext += cipher_char
print("Your ciphertext is: + ciphertext)
