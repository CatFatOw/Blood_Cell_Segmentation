# Blood_Cell_Segmentation

A minimal PyTorch pipeline for segmenting blood cell images. You can change the data to train on your own image/mask pair (although this pipline only works for single class data ie an image cannot contain both cats and dogs, only cats)

---

##  Features

- `DeepLabV3Plus` architecture with `resnet101` encoder
- Custom Dataset support (image + mask pairs)
- Simple training & evaluation loop
- Easy to plug in your own data

---

# Metrics on Testing Data Show (trained for 4 epochs)
```bash
Loss: 0.1219
IOU: 0.8357
Precision: 0.9439
Recall: 0.8800
F1: 0.9108
```

## Prediction Example

An example of the model output on images:

<img src="example_bloodcell_pred.png" alt="Prediction" style="width:1000px; display:block; margin:auto; border-radius:8px; box-shadow:0 0 8px rgba(0,0,0,0.1);" />

---

# How to Run
Just press `shift` + `enter` on each cell


