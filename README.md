# Monstercat vs Cat
Simple Transfer Learning example using TensorFlow Machine Learning library.

## Run it
* Install [Tensorflow](https://www.tensorflow.org/install/)
* Run `python mcat_vs_cat.py /path/to/image.jpg`

###Input
![Drawing of a monstercat's cat in a realistic way](https://github.com/juanferreras/mcat-vs-cat/blob/master/examples/hybrid_1.jpg?raw=true)
###Output
    monstercat (score = 0.94151)
	cat (score = 0.05849)

## Training
* It was trained simply using the `retrain.py` [example provided by TensorFlow](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/image_retraining/retrain.py)
*  Used only 109 images for monstercat and 76 images for cats with surprisingly good results.
