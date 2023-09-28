# DBNs and CNNs for Image Classification

This project wants to exploit a DBN model for its ability to learn an estimation of the probability distribution that have generated the training data, and then reconstruct similar unseen data (in order to **remove noise** or to **neutralize adversarial attacks**).  
The aim is to prove it is useful when paired to a CNN model: firstly corrupted inputs are reconstructed with DBN, then the CNN model will be used to classify reconstructed inputs.  
In conclusion, the pair DBN + CNN will prove to make a **robust model** when dealing with noised inputs, adversarial attacks, or, in general, with corrupted inputs. 
