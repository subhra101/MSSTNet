# MSSTNet
MSSTNet: A Multi-stream Time-distributed Spatio-temporal Deep Learning Model to Detect Mind Wandering from Electroencephalogram Signals

Abstract:
The automated detection of mind-wandering (MW) and associated attention lapses through Electroencephalogram (EEG) signals holds significant potential for practical applications. Traditional handcrafted features have proven inadequate in capturing the spatially and temporally distributed patterns characteristic of MW-EEG signals, limiting the effectiveness of machine learning-based detection models. This study proposes a multi-stream spatio-temporal Deep Learning network (MSSTNet) for automated detection of MW episodes.
In this approach, EEG data from individual frequency bands, extracted directly from raw EEG signals, are fed into distinct feature extraction blocks embedded within each stream of the MSSTNet architecture. These feature extraction blocks comprise time-distributed Convolutional Neural Network—Long Short-Term Memory (CNN-LSTM) modules, enabling the model to capture fine-grained spatio-temporal features across different frequency bands. The CNN layers extract spatial and short-term temporal features, and the LSTM units capture the long-term temporal evolution of these features, which is critical for recognizing prolonged MW episodes. 
The features extracted from each frequency band are subsequently sent to fully connected layers for MW detection. The MSSTNet model is validated on a publicly available MW and focus dataset, achieving a mixed-subject classification accuracy of 95.07\%, substantially outperforming baseline models. Furthermore, the intra-subject and cross-subject classification accuracies of 94.48\% and 83.13\%, respectively, demonstrate the robustness and generalizability of the proposed model. 
The band-wise analysis reveals that the Beta band exhibits the most pronounced alterations due to MW onset. MSSTNet’s capacity to capture subtle spatio-temporal patterns across frequency bands underscores its efficacy as an MW detection framework, with promising scope for broader EEG-based applications.


[cascaded.pdf](https://github.com/user-attachments/files/17269677/cascaded.pdf)
