# inceptionNasnet

You can download the pre-trained weights for this model from
https://drive.google.com/file/d/1DXvg3UW9V8IznDC280l8zGMdbPCz8Tty/view?usp=sharing

To test:

To test the model you can unzip test_selected.zip and refer the path to it in the InceptionNasnet_test.py file.
Run the file using the command
python InceptionNasnet_test.py

To train:

To train the model you need training data which is huge and so not shared but you can follow the lines of creating the train_split_v3.txt for your own training data and train from scratch. 
Or do transfer learning with the weights provided here. All you need to do is
1) create train_split.txt space separated file for your data which contains the labels
2) set train images path and test images path in the InceptionNasnet_train.py file.
