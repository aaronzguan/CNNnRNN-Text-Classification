# CNNnRNN-Text-Classification

Use CNN and RNN to do the Chinese text classification.

## Environment
- Python 2/3
- TensorFlow 1.3 or higher
- numpy
- scikit-learn
- scipy

## DataSet

Used a subset generated from the [THUCNews](http://thuctc.thunlp.org/). This training process used 10 classes and each has 6500 of text data.

[copy_data.sh](https://github.com/aaronzguan/CNNnRNN-Text-Classification/blob/master/copy_data.sh) is used to copy 6500 datas from each of the class, and [cnews_group.py](https://github.com/aaronzguan/CNNnRNN-Text-Classification/blob/master/cnews_group.py) is used to merge multiple files into one file. After executing this file, the below three data files can be obtained:

- Training Data: 5000*10
- Validation Data: 500*10
- Testing data: 1000*10

## Pre-processing

[cnews_loader.py](https://github.com/aaronzguan/CNNnRNN-Text-Classification/blob/master/cnews_loader.py) is used to pre-process the dataset.

## CNN

### CNN Model

### Tranning and Validation

### Testing

## RNN
