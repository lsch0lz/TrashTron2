# TrashTron2

TrashTron2 is a Instance-Segmentation-Model based on [FAIR's Detectron2](https://github.com/facebookresearch/detectron2). TrashTron2 is currently trained on over 200+ Images of trash provided by [TACO](https://github.com/pedropro/TACO).

You can use and train TrashTron2 in the associated [TrashTron2 Notebook](https://colab.research.google.com/drive/1IrutxbF5P1LnbXOjIhMCBu6hJdr5qrjz?usp=sharing) with Google Collab. See the instruction under [GettingStarted](https://github.com/therealgherkhin/TrashTron2/blob/main/GettingStarted.md).

# Outcome

<p align="middle">
  <img src="https://i.imgur.com/lRNhIrW.jpg" width="350" />
  <img src="https://i.imgur.com/E2DwveS.jpg" width="350" /> 
</p>
<p align="middle" >
  <img src="https://i.imgur.com/t63GG42.jpg" width="350" />
  <img src="https://i.imgur.com/cebWJvc.png" width="350" /> 
</p>

# Models

* [ResNext-101](https://arxiv.org/pdf/1611.05431v2.pdf)
* [ResNet-101](https://arxiv.org/pdf/1512.03385.pdf)
* [ResNet-50](https://arxiv.org/pdf/1512.03385.pdf)

# Scores
Model | AP | AP50 | AP75 
--- | --- | --- | --- 
ResNet-50 | 58.314 | 73.825 | 61.755
ResNet-101 | 59.584 | 76.967 | 62.230
ResNext-101 | 59.305 | 78.326 | 63.566

## Accuracy

![Accuracy](https://i.imgur.com/SpIIGzh.png)

## False Negatives

![False-Negatives](https://i.imgur.com/vm75baV.png)

## False Positives

![False-Positives](https://i.imgur.com/xMij5o7.png)

# To-Do's
- [x] release v0.1

- [ ] Increase number of annotated images

- [ ] fine tune models on new images

- [ ] release v0.2

- [ ] deploy Resnet-50 on NVIDIA JetsonNano
