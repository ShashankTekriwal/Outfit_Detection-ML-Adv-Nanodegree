Libraries and Tools
	Python 2.7
	scipy
	pandas
	h5py
	PIL (PILLOW) - https://pillow.readthedocs.io/en/5.1.x/installation.html
	pydensecrf - https://github.com/lucasb-eyer/pydensecrf
	skimage - http://scikit-image.org/
	Caffe (built with Python wrapper) - https://github.com/BVLC/caffe
	DIGITS - https://developer.nvidia.com/digits


Datasets:
	CCP -> https://github.com/bearpaw/clothing-co-parsing
	CFPD -> https://sites.google.com/site/fashionparsing/dataset


CCP and CFPD folders contain:
	feature images from validation set
	ground truth / labels
	prediction from the model
	predictions after crf post processing
	csv file - accuracy and iou metrics for each image


Standard Architecture Definitions along with their pre-trained weights:
	fcn-8s -> https://github.com/shelhamer/fcn.berkeleyvision.org/tree/master/voc-fcn8s
	fcn-16s -> https://github.com/shelhamer/fcn.berkeleyvision.org/tree/master/voc-fcn16s
	fcn-32s -> https://github.com/shelhamer/fcn.berkeleyvision.org/tree/master/voc-fcn32s


My trained models can be found here:
	https://drive.google.com/open?id=1aRm7Cf3IJg0oXY4Yeovqm_BBu8Ksv3tt