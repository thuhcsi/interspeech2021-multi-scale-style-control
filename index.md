# Abstract

This paper introduces a multi-scale speech style modeling method for end-to-end expressive speech synthesis. 
The proposed method employs a multi-scale reference encoder to extract both the global-scale utterance-level and the local-scale quasi-phoneme-level style features of the target speech, which are then fed into the speech synthesis model as an extension to the input phoneme sequence. 
During training time, the multi-scale style model could be jointly trained with the speech synthesis model in an end-to-end fashion. 
By applying the proposed method to style transfer task, experimental results indicate that the controllability of the multi-scale speech style model and the expressiveness of the synthesized speech are greatly improved. 
Moreover, by assigning different reference speeches to extraction of style on each scale, the flexibility of the proposed method is further revealed.