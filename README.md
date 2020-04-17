# covid_lungs_dataset<br>
Images from various internet sources were downloaded and after segmenting the lungs with a Unet, whole dataset was split among tain-test-val:<br>
Following are the sources of dataset:<br>
-Kaggle Pneumonia Detection Competition<br>
-Kaggle RSNA dataset<br>
-https://github.com/ieee8023/covid-chestxray-dataset<br>
-A source from spain on twitter<br>
-A source from italy<br><br><br>

The images in Train, Test and Val for Covid Positive class are from completely different sources. Also Images in Train-Normal and Test-Normal are from completely different sources and VAl-Normal has images mixed from source of Train-Normal and Test-Normal.<br><br>

Following are the number of images in various categories:<br>
1. Train<br>
     -Normal                     : 3199
     -Mild Opacity(noop_ab)      : 2807
     -Lung Opacity or Pneumonia  : 5192
     -Covid Positive             : 152
2. Val:<br>
     -Normal                     : 1035
     -Mild Opacity(noop_ab)      : 786
     -Lung Opacity or Pneumonia  : 1587
     -Covid Positive             : 92
3. Test:<br>
     -Normal                     : 1341
     -Mild Opacity(noop_ab)      : 407
     -Lung Opacity or Pneumonia  : 752
     -Covid Positive             : 116
