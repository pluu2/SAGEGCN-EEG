# GraphSAGE-EEG
A GraphSAGE based EEG analysis


![EEG Layout](https://github.com/pluu2/SAGEGCN-EEG/blob/master/EEG%20images.png)


### To Do: 
----
#### Critical for SOTA: 
- [ ] Kaggle grasp and lift dataset with AUC of 0.981. Need to come close or match.
  - [ ] Need to figure out how to parse the epochs to train the network. The way the epochs are detected is a bit odd but possible. 

#### Tenative 
- [ ] Code an implementation of the physionet left and right hand and rest physionet dataset that can be run consistently with stored weights. This should be a python script, that can run on console. 
- [ ] Create a comparable CNN example to demonstrate SOTA compared to standard. 
- [ ] There has to be an analysis of why training is so unstable. I will have to research "Dev Sets" to ensure consistent results
- [ ] Theoretical analysis of why GNNs work better for EEG analysis than normal CNN. 
