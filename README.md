## Developing a Computationally efficient HybridSN Model
In this Paper, we reduced the computational Complextiy of [Base HybridSN Model](https://github.com/gokriznastic/HybridSN)

## Introduction
This paper suggests using an Inception model between the 3D convolution and 2D convolution to decrease these computations. This research aims to use Indian Pines, University of Pavia, and Salinas Scene remote sensing datasets to lower the computing complexity of the Hybrid SN model while keeping good classification accuracy.

## Model
<img src="https://github.com/chandrakiran08/HybridSN/assets/97818252/1637f785-7962-4591-9df1-9ed22bfed793">
Fig. Proposed Model with an idea of Inception Models between 3D and 2D CNN Layers
## Prerequisites

- [Anaconda 2.7](https://www.anaconda.com/download/#linux)
- [Tensorflow 1.3](https://github.com/tensorflow/tensorflow/tree/r1.3)
- [Keras 2.0](https://github.com/fchollet/keras)

## Results
<img src="https://github.com/chandrakiran08/HybridSN/assets/97818252/9aecc63d-6397-4bbc-bf6e-f99abe8279dd">

## Threshold
We also found the threshold of Inception Model in HybridSN Model
### Indian Pines (IP) Dataset
<img width="1332" alt="IP" src="https://github.com/chandrakiran08/HybridSN/assets/97818252/45783e71-90c7-40d6-b6e6-bea1d0d9a832">

This Figures shows the Average Accuracy, Training Accuracy and Test Accuracy for Various Combination of Inception and CNN Layers

### Salina Scenes (SS) Dataset
![SS](https://github.com/chandrakiran08/HybridSN/assets/97818252/ae17010b-006a-469d-9498-cba912220bb3)

This Figures shows the Average Accuracy, Training Accuracy and Test Accuracy for Various Combination of Inception and CNN Layers

### University of Pavia (UP) Dataset
<img width="1372" alt="UP" src="https://github.com/chandrakiran08/HybridSN/assets/97818252/d7102b9b-beb1-4ad1-9c8e-7f6a4b5f047d">

This Figures shows the Average Accuracy, Training Accuracy and Test Accuracy for Various Combination of Inception and CNN Layers

## Citation

	@article{roy2019hybridsn,
        	title={HybridSN: Exploring 3D-2D CNN Feature Hierarchy for Hyperspectral Image Classification},
		author={Roy, Swalpa Kumar and Krishna, Gopal and Dubey, Shiv Ram and Chaudhuri, Bidyut B},
		journal={IEEE Geoscience and Remote Sensing Letters},
		volume={17},
		no.={2},
		pp.={277-281},
		year={2020}
		}
	@article{roy2020attention,
		title={Attention-based adaptive spectral-spatial kernel resnet for hyperspectral image classification},
		author={Swalpa Kumar Roy, and Suvojit Manna, and Tiecheng Song, and Lorenzo Bruzzone},
		journal={IEEE Transactions on Geoscience and Remote Sensing},
		volume={59},
		no.={9},
		pp.={7831-7843},
		year={2021},
		publisher={IEEE}
		}	
	@article{ahmad2021hyperspectral,
  		title={Hyperspectral Image Classification--Traditional to Deep Models: A Survey for Future Prospects},
  		author={Muhammad Ahmad, and Sidrah Shabbir, and Swalpa Kumar Roy, and Danfeng Hong, and Xin Wu, and Jing Yao, and Adil Mehmood Khan,
		and Manuel Mazzara, and Salvatore Distefano, and Jocelyn Chanussot},
  		journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing},
  		year={2022},
  		volume={15},
  		pages={968-999},
  		doi={10.1109/JSTARS.2021.3133021},
  		publisher={IEEE}
		}
   

## Acknowledgement

Part of this code is from a Implementation of Classification of HSI Using Hybrid-Spectral-Net by [Gopi Krishna](https://github.com/gokriznastic/HybridSN)
