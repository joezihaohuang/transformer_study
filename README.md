# transformer_study


https://d2l.ai/chapter_attention-mechanisms-and-transformers/transformer.html


https://nlp.seas.harvard.edu/annotated-transformer/

https://medium.com/@amniskin/another-annotated-transformer-1c7be3f99e23



https://zenodo.org/records/7754768

https://github.com/wenzhengzeng/MPEblink?tab=readme-ov-file

Nvidia
Jetson Platform and isaac sim



https://ronxin.github.io/wevi/



tokenization is before word embedding

words embedding - giving vector to each word in the sentence 

i    -> 1,2,6,3,6\
like -> 5,6,1,3,6\
cat  -> 1,3,4,5,6\

case 1

the whole sentence is like a matrix similar to image

Then we use CNN or RNN to process the word embedding result

kernal (filter) need to be different! like for case 1 (the kernals have to cover the full word)

kernal example
[1,2,3,4,5]
[1,2,3,4,5]
[1,2,3,4,5]

 -> after embedding the result looks like a picture we could use CNN to processing this form of data with the special kernals
 
1, word embedding happened before training? yes

2, token? is one word or the whole sentence? tokenization is before the word embedding

3, Gemini running on local machine? 

MMLU test

MMMU test evaluation


https://ollama.com/
