#first we need to define parameters and arguments with functions
#encryption function is define with the formulas we will be using further
  def encryption(plain_text, shift_key):
    cipher_text = ""
    for char in plain_text:
        if char in alphabet:
            position = alphabet.index(char)
            new_position = (position + shift_key) % 26
            cipher_text += alphabet[new_position]
        else:
            cipher_text += char
    print(f"heres is the text after encryption:{cipher_text}")

#decryption function is define with the formulas we will be using further
def decryption(shift_key, cipher_text):
    plain_text = ""
    for char in cipher_text:
        if char in alphabet:
           position = alphabet.index(char)
           new_position = (position - shift_key) % 26
           plain_text += alphabet[new_position]
        else:
            plain_text += char
    print(f"heres is the text after decryption:{plain_text}")
