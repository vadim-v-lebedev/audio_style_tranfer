# Audio Style Transfer

This is an implementation of famous artistic style tranfer algorithm for audio, which uses convolutions with random weights to represent audio features. 
Example inputs and outputs are available in corresponding directories 

**References**
- Original paper on style tranfer:
https://arxiv.org/abs/1508.06576
- Style transfer implementation in lasagne recipes:
https://github.com/Lasagne/Recipes/blob/master/examples/styletransfer/Art%20Style%20Transfer.ipynb
- Publications on texture generation with random convolutions:

 - https://nucl.ai/blog/extreme-style-machines/
 - https://arxiv.org/abs/1606.00021
 - https://arxiv.org/pdf/1606.04801

**Dependencies:**
- theano with lasagne
- librosa
- numpy and matplotlib
