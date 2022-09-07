# Emotion-Recognition-using-EEG
<h3>Disclaimer</h3>
</strong></p>This repo is just for training and educational purposes.</strong></p>
<h3>Introduction</h3>
</strong></p>Recognizing emotional states from the brain signals is one of the most significant advantages of electroencephalogram (EEG) analysis using deep learning methods. A major challenge in EEG-based emotion recognition is EEG analysis is time-consuming, complex and difficult.The method we discuss in this work would be EEG analysis without feature extraction and without the use of the sliding window. In this work, we seek to use one-dimension Neural Networks to classify emotions using EEG signals from the Database for Emotion Analysis using Physiological Signals<a href="https://www.eecs.qmul.ac.uk/mmv/datasets/deap/"_blank" rel="noopener noreferrer">(DEAP).</a> This research considers two different labels, one is the classification of four classes of emotions such as low arousal and low valence (LALV), low arousal and high valence (LAHV), high arousal and high valence (HAHV), and high arousal and low valence (HALV), and the other is high valence (HV) and low valence (LV).</strong></p>
</strong></p>The average accuracy for classifying four emotional ranges reached 97.7 % by CNN_1, 97.1% by CNN_2, and 99.5% by CNN-LSTM. Also, Our methods achieved 100%, 98.8%, and 99.7% accuracy respectively by CNN_1, CNN_2, and CNN-LSTM in the EEG emotion classification for HV and LV labels.</strong></p>

<h3>Description of the project</h3>
First of all, by using <a href="https://github.com/ieee8023/covid-chestxray-dataset/" target="_blank" rel="noopener noreferrer">MNE.</a> python libarary, we converted the EEG signals to a time series array. 
  
  @article{GramfortEtAl2013a,
  title = {{{MEG}} and {{EEG}} Data Analysis with {{MNE}}-{{Python}}},
  author = {Gramfort, Alexandre and Luessi, Martin and Larson, Eric and Engemann, Denis A. and Strohmeier, Daniel and Brodbeck, Christian and Goj, Roman and Jas, Mainak and Brooks, Teon and Parkkonen, Lauri and H{\"a}m{\"a}l{\"a}inen, Matti S.},
  year = {2013},
  volume = {7},
  pages = {1--13},
  doi = {10.3389/fnins.2013.00267},
  journal = {Frontiers in Neuroscience},
  number = {267}
}
