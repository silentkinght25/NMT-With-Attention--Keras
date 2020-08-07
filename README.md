# NMT-Encode-Decoder-With-Attention-implemented-in-Keras
I have implemented Encoder Decoder with Attention model for French to English language neural machine translation. The dataset has been attached you can download it. I have used GRU RNN, and this model gives a good accuracy for short sentences, but might not perform well for long sentences, for better performance use LSTM and different dataset which is pretty large enough. I have only used 100000 sentences and a single layer GRU is used. Note: adding more layers will significantly increase the training time. If have trained this model for 10 epoch using a GPU for about an hour. Moreover here I have implemented custom gradient descent, where you can modify the loop as required. This feature is new in tensorflow 2.0.0.  
Two files are available:
1. French to English translation
2. English to hindi translation
