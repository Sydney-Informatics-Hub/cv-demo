# cv-demo

## Introduction 

Self driving cars. Face recognition. X-Ray, CT and MRI analysis. Digital pathology. These are just the tip of the iceberg of applications for a technology called computer vision. 

We've had cameras and computers for a long time, but now we have the technology to make our computers understand the pictures and videos captured by our cameras. 
Researchers around the world are competing to develop better and better computer vision algorithms that can understand and make predictions about pictures. One of the most famous models is called YOLO: You Only Look Once. 
YOLO models have state of the art prediction speed, allowing computers to make extremely fast descisions about images they are seeing.

From a research perspective, the incredibly exciting thing about many of these models is that we can take algorithms developed by Facebook, Netflix, Google and the R&D departments of other tech giants, and apply them to completely different datasets that are part of our research. This enables us to get really cool results we can use to better understand our world - and to publish exciting, high-impact papers. 

In this workshop, we'll show you how you can take a YOLO model that has been trained to solve a problem on one dataset, and then fine tune the model to solve a similar problem but with a totally new dataset.
You'll learn the basic concepts behind computer vision and transfer learning, and will be shown how to use industry leading open source tools in Python, including Pytorch and torchvision, and how to use them on cloud computing virtual environments so that you can get access to powerful CUDA enabled GPUs to accelerate machine learning.

# Setup

## Locally

### Requirements

* Conda
* Python

```bash
conda create env -n cvdemo -python=3.9

conda activate cvdemo

pip install -r requirements.txt
```

```bash
jupyter-lab
```

Follow the rest of the instructions in the Jupyter notebook.

## Google Colab 

Or, if you don't have access to a CUDA capable GPU locally, try it out in a jupyter notebook on a [Google Colab GPU VM](https://colab.research.google.com/drive/1uAt8aTkBXBvwWzAW58842o26jcEVc1DX?usp=sharing).
