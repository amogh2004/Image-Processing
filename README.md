# ImageProcessing-ML

## PS:
Jupyter Notebooks are a powerful way to write and iterate on your Python code for data analysis. Rather than writing and re-writing an entire program, you can write lines of code and run them one at a time, thus giving you a better flexibility to run the code.

### Handwriting Recognition 1
Using the MNIST data set, a collection of 70,000 handwriting samples of numbers 0-9, we predict which number each handwritten image represents using TENSORFLOW(with multi-level perceptrons).

### Handwriting Recognition 2
Using the MNIST data set, a collection of 70,000 handwriting samples of numbers 0-9, we predict which number each handwritten image represents using a Convolutional Neural Network that's better suited for image processing. CNN's are less sensitive to where in the image the pattern is that we're looking for.

### Transfer Learning
Using the ResNet50 model, trained on the imagenet data set, in order to quickly classify new images. The ResNet50 pre-trained CNN expects inputs of 224x224 resolution, and will classify objects into one of 1,000 possible categories.

## Warning!
These programs could take hours to run, and your computer's CPU will be maxed out during that time! Don't run **HandWritingRecc2.ipynb** unless you can tie up your computer for a long time. It will print progress as each epoch is run, but each epoch can take around 20 minutes.
