## Developing a Computationally Efficient HybridSN Model
In this Paper, we reduced the computational Complextiy of [Base HybridSN Model](https://github.com/gokriznastic/HybridSN)

## Introduction
This paper suggests using an Inception model between the 3D convolution and 2D convolution to decrease these computations. This research aims to use Indian Pines, University of Pavia, and Salinas Scene remote sensing datasets to lower the computing complexity of the Hybrid SN model while keeping good classification accuracy.

## Model
<img src="https://github.com/chandrakiran08/HybridSN/assets/97818252/0c8dcce4-a5db-4d80-aa1f-ab90dc817540">
Fig. Proposed Model with an idea of Inception Models between 3D and 2D CNN Layers

## Prerequisites

- [Anaconda 2.7](https://www.anaconda.com/download/#linux)
- [Tensorflow 1.3](https://github.com/tensorflow/tensorflow/tree/r1.3)
- [Keras 2.0](https://github.com/fchollet/keras)

## Results
<img width="981" alt="Results" src="https://github.com/chandrakiran08/HybridSN/assets/97818252/d3b53b16-ae9c-48ec-b1aa-86535acd9eba">

And the table below shows the results specific to Indian Pines Dataset compared to Original Hybrid SN Model.
<img width="579" alt="Results IP" src="https://github.com/chandrakiran08/HybridSN/assets/97818252/3c513a1c-546d-40e1-bdd4-ba5cdf45c627">

## Threshold
We also found the threshold of Inception Model in HybridSN Model
### Indian Pines (IP) Dataset
<img width="1357" alt="IP" src="https://github.com/chandrakiran08/HybridSN/assets/97818252/b7808c9d-ab02-4929-9a05-baa92d3df4ce">

This Figures shows the Average Accuracy, Training Accuracy and Test Accuracy for Various Combination of Inception and CNN Layers

### Salina Scenes (SS) Dataset
<img width="1349" alt="SS" src="https://github.com/chandrakiran08/HybridSN/assets/97818252/d64e192d-e556-4c3c-a66a-ade1b0284e4c">


This Figures shows the Average Accuracy, Training Accuracy and Test Accuracy for Various Combination of Inception and CNN Layers

### University of Pavia (UP) Dataset
<img width="1350" alt="PU" src="https://github.com/chandrakiran08/HybridSN/assets/97818252/a980209a-260d-45c0-b169-75a4c9139065">


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
