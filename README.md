# Tiny-imagenet-200
Classification of Tiny-Imagenet-200 dataset without any pretrained weights

## Architecture Used

Densenet-201 with a shallow network with following layers:
- GlobalAveragePooling2D()
- Dropout(0.4)
- Softmax layer of 200 units.

## Accuracy 

- Top-1 : 31.69%
- Top-5 : 57.58%

## Error

- Top-1 :2.99
- Top-5 :2.99
