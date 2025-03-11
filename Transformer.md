# Transformers
Transformers is developed by Google reachers in 2017. It change the way how AI understand, generate, and do complex reasoning. Before transformer AI is strugle to remember long context and it get confuse sometime when similar words come which means it is unable to understand the context of sentence because old model is using RNN and LSTM to overcome this problem transformers comes into picture.

## Key Feature of Transformer:

- Self- Attention Mechanism
- Position Encoder
- Multi-Head Attention
- Feedforward layers
- Layer Normalization

1) Self- Attention Mechanism: Help model to understand relationship between word. Example: In a Movie called ROBOT when Dr. Vasikaran first make Chitti he uses RNN Chitti in intial stage can't understand the context of word after when robot get rejected it uses Transformer after that Chitti is able to under the context

2) Position Encoder: Help to bind the words into fix position so that it understand the word order. 

3) Multi-Head Attention: It allow to focus on diffrent word at same time. Which reduce time to process each words seprately. Example: Allow Chitti to process multiple words at same time

4) Feedforward layers: It is aditional layer that refine understanding

5) Layer Normalization: Helps the model train faster and work more efficently

## How transformer works step by step process?

1) Encoder: Read and process the input
2) Decoder: Generate the output based on processed info

## Step of transformer:

Step 1: Tokenization

Step 2: Positional encoding

Step 3: Self-Attention Mechanism

Step 4: Multi-Head Attention

Step 5: Feedforwrd

1) Tokenization: In this step input is divided into small pieces called token.
2) Positional encoding: This step Help to bind the words into fix position so that it understand the word order
3) Self-Attention Mechanism: After fixing the position it help model to understand relationship between word
4) Multi-Head Attention: It help to understand diffrent word at same time
5) Feedforward: In this step it refine the understanding
6) Otput: This is last step in this step model genrate output

## How AI Transformer changed 

- It solve the problem which is traditional model like RNN can't able to solve it like memorizing long relationship between text

- It is fast because it uses multi head attention

- They not only takes input with text it uses multi-models


