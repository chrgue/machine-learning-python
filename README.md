# Machine Learning with Python

_Note: This repository is currently under construction!_
</br>

This repository is my playground for getting in touch with machine learning.


It currently contains notebooks, which I use as cheat sheets respectively playground for libraries like [numpy](http://www.numpy.org/), [pandas](https://pandas.pydata.org/), [scikit-learn](http://scikit-learn.org) and [mathplotlib](https://matplotlib.org/).

In addition build models for dummy problems.

Current dummy problems:
* Classify Urls (01_classification_url)


</br>

To view, run and edit the notebooks you just need to run the following commands. (I assume you have docker installed and your user is in the docker group)

```bash
git clone git@github.com:chrgue/machine-learning-python.git
cd machine-learning-python
docker run -it --name notebook --rm -p 8888:8888 -v <PATH_TO_REPOSITORY>:/home/jovyan/work jupyter/scipy-notebook
```

Visit the url you see in the terminal.
</br>

Something like _http:localhost:8080?token=[TOKEN]_.


