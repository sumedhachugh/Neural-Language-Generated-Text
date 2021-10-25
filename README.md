# Empirical Laws of Natural Language Processing for Neural Language Generated Text


Many sequence models show great work in generating human like text, but the amount of research work done to check the extent up to which their results match the man-made texts are limited in number. 

In this paper, the text is generated using Long Short Term Memory networks (LSTMs) and Generative Pretrained Transformer-2 (GPT-2). The text by neural language models based on LSTMs and GPT-2 follows Zipf’s law and Heap’s law, two statistical representations followed by every natural language generated text. One of the main findings is about the influence of parameter Temperature on the text produced. The LSTM generated text improves as the value of Temperature increases. The comparison between GPT-2 and LSTM generated text also shows that text generated using GPT-2 is more similar to natural text than that generated by LSTMs.

#### Sherlock.txt: Dataset
#### LSTM_Text_Generator_colab.ipynb: Explored and cleaned dataset, tuned hyper-parammeters and generated LSTM model 
#### LSTM_Text_Exploration.ipynb: Generated text using model generated in previous N.B Verified Zipf's and Heap's law on data generated
#### Transformers_Text_generation.ipynb: Generated text using transformers (Source Referenced:: https://www.youtube.com/watch?v=vSN5Tn38ZIc&list=PL0Gv4uEEcwwDW6Q5AxxlektvPjeK9g_cJ&index=1. https://github.com/raghavbali/text_generation/blob/master/notebooks/text_generation_03.ipynb)


