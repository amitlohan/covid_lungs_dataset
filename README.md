# covid_lungs_dataset
Images from various internet sources were downloaded and after segmenting the lungs with a Unet, whole dataset was split among tain-test-val: 
Following are the sources of dataset:
Kaggle Pneumonia Detection Competition
Kaggle RSNA dataset
https://github.com/ieee8023/covid-chestxray-dataset
A source from spain on twitter
A source from italy

The images in Train, Test and Val for Covid Positive class are from completely different sources. Also Images in Train-Normal and Test-Normal are from completely different sources and VAl-Normal has images mixed from source of Train-Normal and Test-Normal.

Following are the number of images in various categories:
Train:
     Normal                     : 3199
     Mild Opacity(noop_ab)      : 2807
     Lung Opacity or Pneumonia  : 5192
     Covid Positive             : 152
Val:
     Normal                     : 1035
     Mild Opacity(noop_ab)      : 786
     Lung Opacity or Pneumonia  : 1587
     Covid Positive             : 92
Test:
     Normal                     : 1341
     Mild Opacity(noop_ab)      : 407
     Lung Opacity or Pneumonia  : 752
     Covid Positive             : 116
