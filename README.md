# Winogrande_CHATGPT
The evaluation of Winogrande Debiased Validation set on ChatGPT

So far I could found the chance to ask for 90 samples and hit the limits. I will continue whenever I have access again.

Sometimes the model answers like **Option1: Answer**, and sometimes it only responds with a single number.
I decided to ask model to explain the answers. You can find the explanations in the dataframe.

Here is the generic text:
```
Choose the option that is a better fit for the gap in the sentence. The answer should be in following form:
'''
 OptionX
 Explanation: ...
'''
Sentence : {}
    
Option1 : {}
Option2 : {}
```
The accuracy over 310 samples: %68.04


```
Choose the option that is a better fit for the gap in the sentence. Do not explain. Only say 1 or 2
Sentence : {}
    
Option1 : {}
Option2 : {}
```
I will update this page regularly.
