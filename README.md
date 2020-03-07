[towardsdatascience.com - article](https://towardsdatascience.com/image-similarity-detection-in-action-with-tensorflow-2-0-b8d9a78b2509)

# ImageSimilarityDetection
Image Similarity Detection in Action with Tensorflow 2.0 - Annoy and Angular

## CNN
Currently MobileNet is used, but it can easily changed to a different network.
[edit line 61 in get_image_feature_vectors.py](https://github.com/RedTo/ImageSimilarityDetection/blob/772772cf9a881c818009c9120fc3478a335610f9/get_image_feature_vectors.py#L61) and use one of those models listed here: [TensorFlow Hub](https://tfhub.dev/google/collections/image/1)
