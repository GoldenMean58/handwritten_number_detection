# handwritten_number_detection
Detect the handwritten number with Tensorflow Keras datasets API and mnist database.

# Installation
1. Install python3.7.4 and `python-tk`
2. Install requirements(tensorflow==1.14.0, Keras==2.2.5, matplotlib==3.1.1, Pillow==6.1.0, numpy==1.17.1)

	Run `pip install -r requirements.txt --user` in the directory

# Usage
1. Run the python script `python3 main.py`. It will download mnist databases automatically.
2. It will prompt a menu with four options, and then you can detect the handwritten numbers in the mnist databases with 10000 pictures for test or draw and detect your hand written numbers. Or compile and fit your own model.

# Note
1. The fitted model is named as `my_model.h5`, and I had finished a model for you, so you can run detection directly.
