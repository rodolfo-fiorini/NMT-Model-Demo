# NMT-Model-Demo
Neural Machine Translation with Encoder Decoder RNN Model - Spanish to English

# Problem Statement: 
I implemented a Neural Machine Translation model that consists of translating a Spanish sentence into an English sentence using an Encoder-Decoder network with the ability to visualize the contextual words from the input each translated word consists of through a correlation matrix. 

# Dataset: 
Downloaded data from a zip file called spa-eng.zip at www.manythings.org/anki. Wrangled data to a list of sentence pairings containing Spanish and English sentences with equivalent meanings. 

# Seq2Seq Model Architecture: 
The model consists of an Encoder and a Decoder network implemented with an Attention mechanism. Both the Encoder and Decoders are composed of multilayer GRU stacks. The Encoder received Spanish sentences as inputs and filters them into a latent space with outputs that feed into the decoder network. The Decoder network then translates the Spanish sequence of words into an English sequence. The attention mechanism included helps emphasize the contexts of each word from the input sentence for proper translations when multiple words are relevant to a translation. 

