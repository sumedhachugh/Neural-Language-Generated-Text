# Natural-Language-Statistical-Features-of-neural-language-Generated-pseudo-Text
In the field of NLP (Natural Language Processing) the latest work is being done for Text Generation, as the machines are designed to focus on customer demand, identify important business information and prepare surrounding summaries that leads to the reduction in personal involvement. Long Short Term Memory networks (LSTMs) have recently shown remarkable performance in a number of activities dealing with natural language production, such as writing captions for imagery or poetic composition. However, only a handful of works have analyzed the text produced by LSTMs in order to assess the extent to which these scripts are identical to the man-made ones.

In this project I have generated text using LSTMs and Transformers and have shown that the neural language model based on LSTMs follows Zipf’s and Heap’s law, two statistical representations followed by every natural language generated text. The main findings are about how a specific parameter known as Temperature affects the quality of the text produced and the confirmation that the text produced using Transformers is of better quality than that produced by LSTMs.

### Research Papers refrenced: 

--- Natural Language Statistical Features of LSTM-Generated Texts by Marco Lippi , Marcelo A. Montemurro , Mirko Degli Esposti, and Giampaolo Cristadoro Published in IEEE Transaction on Neural Networks and Learning Systems, VOL. 30, NO. 11, dated NOVEMBER 2019
Link: https://ieeexplore.ieee.org/document/8681285


--- Another research paper referenced is: Poem Generation using Transformers and Doc2Vec Embeddings by Marvin C. Santillan Arnulfo P. Azcarraga, College of Computer Studies De La Salle University Manila, Philippines, 978-1-7281-6926-2/20/$31.00 ©2020 IEEE
Link: https://ieeexplore.ieee.org/document/9207442

--- Do Neural Nets Learn Statistical Laws behind Natural Language? by Shuntaro Takahashi1†, Kumiko Tanaka-Ishii2‡, The University of Tokyo,Japan.

### Repos Refrenced: 

https://github.com/raghavbali/text_generation

Can't upload generated model as its size is > 25MB

#### Sherlock.txt: Dataset
#### LSTM_Text_Generator_colab.ipynb: Explored and cleaned dataset, tuned hyper-parammeters and generated LSTM model 
#### LSTM_Text_Exploration.ipynb: Generated text using model generated in previous N.B Verified Zipf's and Heap's law on data generated
#### Transformers_Text_generation.ipynb: Generated text using transformers (Credits: https://www.youtube.com/watch?v=vSN5Tn38ZIc&list=PL0Gv4uEEcwwDW6Q5AxxlektvPjeK9g_cJ&index=1. https://github.com/raghavbali/text_generation/blob/master/notebooks/text_generation_03.ipynb)
