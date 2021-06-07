# Image Classification using Convolutional Neural Networks

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/voiculaura/

This project is an attempt to improve the image classification project developed for the EPFL "Applied Data Science and Machine Learning Program". The goal of the original project was to build an image classifier using the Swissroads data set which contains a couple of hundreds of images of vehicles found in the EPFL - Lausanne area categorized as cars, trucks, vans, bikes, motorcycles and others (only 280 training samples). There were 2 explicit goals for this project: one: to test and compare traditional ML classifiers, with no restriction on how to get around the fact that we only have 280 training samples and two: to build a CNN trained on the 280 samples and find different techniques to improve its performance.

Improvements with respect to the original project:

- Data Augmentation
- Normalization: Pixel normalization, pixel centering, pixel standardization (sample-wise/feature-wise)
- Color space transformations
- Model/ Hyperparameter tuning

Some other ideas worth exploring:

- Different data augmentation (generative model)
- Regularization techniques (L2 to force small parameters, L1 to set small parameters to 0), different activation/optimizer, filter sizes, learning rate reduction on plateau, color space transformation…)
- Retrain on wrongly predicted training images (fine tune the model to specific set of images for which it previously miss predicted).
- Ensembles or make a gradient boosted tree of neural networks.

Blogs: 
- (Part 1): https://lauravoicu.github.io/Post-2.html
- (Part 2): https://lauravoicu.github.io/Post-3.html

## Contributing

I use this for my own projects, I know this might not be the perfect approach for all the projects out there. If you have any ideas, just [open an issue][issues] and tell me what you think.

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

## License

Distributed under the MIT License. See `LICENSE` for more information.
