# Winogrande_CHATGPT
The evaluation of Winogrande Debiased Validation set on ChatGPT


So far I could found the chance to ask for 310 samples and hit the limits. I will continue whenever I have access again.
### The accuracy over 310 samples: %68.04


Sometimes the model answers like **Option1: Answer**, and sometimes it only responds with a single number.

I decided to ask model to explain the answers. You can find the explanations in the dataframe.

### Generic text:
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

#### Old generic text:
```
Choose the option that is a better fit for the gap in the sentence. Do not explain. Only say 1 or 2
Sentence : {}
    
Option1 : {}
Option2 : {}
```
I will update this page regularly.

Citation to the author's paper
```
@InProceedings{ai2:winogrande,
title = {WinoGrande: An Adversarial Winograd Schema Challenge at Scale},
authors={Keisuke, Sakaguchi and Ronan, Le Bras and Chandra, Bhagavatula and Yejin, Choi
},
year={2019}
}
```
