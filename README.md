# NMT-Using-the-Attention-Based-Model
The source text  is first fed into the encoder, which transforms it into a thought vector. This dense representation is then fed into a decoder, along with the original translation in the target language during training. This serves as preconditioning on the decoder, which learns the corresponding translation based on the original translation that's fed while training

The encoder may not be able to capture long-term dependencies. To overcome this problem, the attention mechanism was introduced by Bahdanau et al.(2014). 

I have enclosed this paper in this repository 

Bleu Score :0.37 
