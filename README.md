# Encryption-Decryption-Using-Vigenere-Cipher

## 🔒 Introduciton
In this modern age of the Internet and big data, privacy has become a major concern to everyone. With more and more platforms adopting encryption to their transactions and messages, I propose a simple encryption and decryption system which will encode and decode your message using Vigenere cipher. Vigenere cipher is an example of polyalphabetic cipher which is based on substitution, using multiple substitution alphabets. This ensures that your message is safe from others and makes sure your message can only be read by the intended recipient with the key.

## 🤔 How it Works?
Vigenere cipher 
: It is an advanced version of the classic Caesar cipher. It consists of 26 Caesar ciphers with shifts of 0 to 25.

    Encryption Process :
      Ci = (Pi + Ki mod m) mod 26

    Decryption process :
      Pi = (Ci - Ki mod m) mod 26

GUI
: The second aspect of this project is the GUI. I use python's Tkinter package for designing a simple GUI interface. I use its in-built functions for creating a window, buttons, and labels.

## 🚀 How to use?
You type the message you want to encrypt in the “Message” field and the encryption key in the “Key” field. The Key can be a combination of
letters and digits and should be remembered to decrypt the message back. The third field “Mode”, determines whether we want to encrypt or decrypt the message by inputting either “e” for encrypt or “d” for decrypt”. Finally you click “Show Message” to see the encrypted message in the “Result” field. The decryption process is very similar, in that you put the encrypted message in the “Message field”, input the Key and then select “d” in the Mode field. Then you click “Show Message” to get the original message in the “Result” field.

There are also two additional buttons for resetting all values and closing the window, labeled “Reset” and “Exit” respectively.

## 🔑 Output
### Encryption

![python_sCrUXkH9vA](https://user-images.githubusercontent.com/102208188/180246551-86c55457-0b4a-4681-9b5c-6581776116f8.png)

### Decryption
![python_V9Gw3nwckv](https://user-images.githubusercontent.com/102208188/180246639-72e7d50a-8c6c-4b9b-b0fa-7eafcfe64e29.png)


## ✅ Conclusion

Sucessfully encrypt and decrypted messages. The drawback of Vigenere Cipher is if the key length is smaller than the plaintext length, then the key will be repeated, because of this it is more vulnerable than other, more secure ciphers. Finally, thi project can be used as a foundation for implementing other ciphers.
