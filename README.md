[//]: # (Image References)
[image1]: https://greydanus.github.io/assets/enigma-rnn/vigenere.gif "vigenere"
[image2]: https://greydanus.github.io/assets/enigma-rnn/enigma.gif "enigma_gif"
[image3]: enigma_examples.png "enigma_DL"
[image4]: vigenere_examples.png "vigenere_DL"
# dl_enigma

Main goal of this repo is to crack different text-encrypting techniques like reported in the post: https://greydanus.github.io/2017/01/07/enigma-rnn/

1. Vigenere:

![vigenere][image1]

Vigenere_\*.ipynb: shows the ability of RNN based approaches to crack the simple Vigenere code:

![vigenere_DL][image4]

2. Enigma:

![enigma_gif][image2]

Once the ability to crack a text code is proven with Vigenere, we reuse the same approach to crack the enigma machine from nazi germany to see if we could help Alan Turing's team:

![image3]

For both cases, the algorithms are able to crack the code, RNN being slower than LSTMs to solve
