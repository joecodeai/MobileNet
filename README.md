# MobileNet and VGG16 image classification

Small Keras experiments with ImageNet-pretrained classifiers: load MobileNet and VGG16, preprocess
your own photos to 224x224, and decode the top-5 ImageNet predictions. Useful for comparing a
lightweight mobile architecture with a much larger one on the same inputs.

| Notebook | Model |
|---|---|
| `KerasMobileNet.ipynb` | MobileNet v1 (about 4.2M parameters) |
| `KerasVgg.ipynb` | VGG16 (about 138M parameters) |

Sample inputs are in `MobileNet-samples/`. `model.csv` holds exported predictions.

## Run

```bash
pip install tensorflow numpy pillow jupyter
jupyter lab
```

Change the image folder path in `prepare_image()` to point at `MobileNet-samples/`.

## Stack
Python · TensorFlow / Keras

## Licence
MIT
