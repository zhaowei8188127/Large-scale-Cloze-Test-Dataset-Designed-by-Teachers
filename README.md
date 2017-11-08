# Large-scale Cloze Test Dataset Designed by Teachers

Code for the paper:

[Large-scale Cloze Test Dataset Designed by Teachers]. Qizhe Xie*, Guokun Lai*, Zihang Dai and Eduard Hovy.

## Dependencies
* Python 2.7
* Pytorch

## Usage
* tar xzvf data.tar.gz
* test the best model: bash test.sh
* download glove embedding to replace embed/glove.6B.300d.txt http://nlp.stanford.edu/data/glove.6B.zip
* training the best model: bash train.sh

## Acknowledgement
* The code is adapted from OpenNMT (https://github.com/OpenNMT/OpenNMT-py) and Pytorch language model example (https://github.com/pytorch/examples/tree/master/word\_language\_model)
* The code to highlight informative words (Figure 1 in the paper) is available at https://gist.github.com/ihsgnef/f13c35cd46624c8f458a4d23589ac768

## Contact
* Please contact Qizhe Xie (qizhex AT cs cmu edu) if you have questions

## License
MIT
