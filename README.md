# University Programming Integration Project
What i've done for the uni integration project.

This repo includes 3 ipynb files:
- `MNIST_DEMO.ipynb`: simple CNN model trained on the MNIST dataset to to classify if the number in the image is 0-9
- `Polygon_DEMO`: a more complex CNN model trained on the [gonzalorecioc/color-polygon-images](https://www.kaggle.com/datasets/gonzalorecioc/color-polygon-images) dataset to classify whether a polygon is a 3-gon, 4-gon, 5-gon or 6-gon
- `CIFAR10_DEMO.ipynb`: the most complex CNN model (out of three), trained on the CIFAR10 dataset to classify 10 classes. The file includes `Net3x3`, `Net3x3Norm`, `Net5x5`, `Net2x3x3Normless` and `Net2x3x3`, each is an improvement over the last one.
- `GPT_DEMO.ipynb`: small GPT model trained on `truyenkieu.txt` to generate poems. It does not do it very well. This also has the least effort put on because I wasn't really interested in LM/NLP

For the 3 CNN demos, I also include Grad-CAM visualization, so I could hopefully get extra mark.

# References
[What the fuck is Grad-CAM](https://arxiv.org/abs/1610.02391)

https://en.wikipedia.org/wiki/MNIST_database

https://en.wikipedia.org/wiki/CIFAR-10

[In case you missed it, here's the polygon dataset](https://youtu.be/dQw4w9WgXcQ)
