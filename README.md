This is a experimental results for the paper ["Friendship Paradox Biases Perceptions in Directed Networks"](https://arxiv.org/abs/1905.05286). You can find the dataset used for this experiments in [Open Science Framework](https://osf.io/pjkr9/). All the results of running the code on real data are saved in the notebook of the repository. 


# System Requirements
## Hardware requirements
A standard computer with enough RAM to support the in-memory operations would be enough to run the experiments. 

## Software requirements
### OS Requirements
This package is supported for any system with Jupyther notebook installed. It has been tested on macOS Mojave (10.14.5).

### Python Dependencies
Python 3.7 have been used to run the experiments. The following python packages are required to run the experiments:
```
numpy
scipy
pandas
matplotlib
seaborn
```
You can install packages using `pip` or `conda`. 

### Run
After installing required packages in python, you need to run all cells of [`Friendship Paradox Biases Perceptions in Directed Networks.ipynb`](https://github.com/ninoch/perception_bias/blob/master/Friendship%20Paradox%20Biases%20Perceptions%20in%20Directed%20Networks.ipynb) file. The results would be shown in output of each cell. You can find generated figures in `/Plots`, and pickles of processed data in `/store_results`. It took 1-2 days to run the program on macbook Pro for real data. For the small synthetic generated data it took less than 5 minutes. 

# Cite
Please cite our paper if you use this code or data in your own work:

	@article{alipourfard2019friendship,
	  title={Friendship Paradox Biases Perceptions in Directed Networks},
	  author={Alipourfard, Nazanin and Nettasinghe, Buddhika and Abeliuk, Andres and Krishnamurthy, Vikram and Lerman, Kristina},
	  journal={arXiv preprint arXiv:1905.05286},
	  year={2019}
	}
