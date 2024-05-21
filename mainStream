# This will the main body that will be connected by user
# here we used loop to continue the stream
# also the conditional statements for encrypt and decrypt
wanna_end =False
while not wanna_end:
    what_to_do = input("type 'encrypt' for encryption, type 'decrypt' for decryption:\n")
    text = input("type your message:\n")
    shift = int(input("enter shift key:\n"))
    if what_to_do == "encrypt":
        encryption(text, shift)
    elif what_to_do == "decrypt":
        decryption(text, shift)
    play_again = input("type yes to continue, type no to stop:")
    if play_again == 'no':
        wanna_end = true
        print("have a nice day bye")
    else:
        print("lets go again")
