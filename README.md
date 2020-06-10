# GraphSAGE-EEG
A GraphSAGE based EEG analysis


![EEG Layout](https://github.com/pluu2/SAGEGCN-EEG/blob/master/EEG%20images.png)


### To Do: 
----
#### Critical for comparison: 
- [ ] Repeated analysis of BCI II Data IV results on Conv2D and GraphSageGCN. 
  - [ ] Initial data has demonstrated that GraphSAGEGCN out performs standard Conv2Ds in certain EEG classification tasks. I have noted that I have to wait for complete convergence of the model in order to make a conclusion about the analysis. Also I should not be direclty examining the testing data. 
#### Tenative 
- [ ] Code an implementation of the physionet left and right hand and rest physionet dataset that can be run consistently with stored weights. This should be a python script, that can run on console. 
- [ ] Create a comparable CNN example to demonstrate SOTA compared to standard. 
- [ ] There has to be an analysis of why training is so unstable. I will have to research "Dev Sets" to ensure consistent results
- [ ] Theoretical analysis of why GNNs work better for EEG analysis than normal CNN. 
