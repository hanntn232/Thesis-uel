## Installation

We suggest the use of Google Colab for running this code

Step 1: download project from https://github.com/hanntn232/Thesis-uel.git
Step 2: upload the project folder to Google drive (with Google Colab pro subcription)

## Dataset

**VISUELLE2** dataset is publicly available [here](https://forms.gle/8Sk431AsEgCot9Kv5). Please download and extract it inside the root folder. A more detailed description of the dataset can be found in the [project webpage](https://humaticslab.github.io/forecasting/visuelle).  

## Run Naive and Simple Exponential Smoothing baselines
Run forecast_stat.ipynb file in google colab pro environment 
Follow to the flow Initialize --> [Chose the method with the corresponding approach]

## Run RNN with image attention + RNN with multi-model attention
Step 1: Run train_dl.ipynb file: Initialize --> [Chose the method with the corresponding approach]
Step 2: Run forecast_dl.ipynb file: Initialize --> [Chose the method with the corresponding approach] (set args.ckpt_path is the path gained from step 1)

## Citation
If you use the **VISUELLE2.0** dataset or this particular implementation, please cite the following paper:

```
@inproceedings{skenderi2022multi,
  title={The multi-modal universe of fast-fashion: the Visuelle 2.0 benchmark},
  author={Skenderi, Geri and Joppi, Christian and Denitto, Matteo and Scarpa, Berniero and Cristani, Marco},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={2241--2246},
  year={2022}
}
```
