# Machine Learning with Python

This repository is my playground for getting in touch with machine learning.


It currently contains notebooks, which I use as cheat sheets for numpy, pandas and mathplotlib. (00_...) and models for dummy problems.

Dummy Problems:
* Classify Urls (01_classification_url)


To view, run and edit the notebooks you just need to run the following commands. (I assume you have docker installed and your user is in the docker group)

```bash
git clone

docker run -it --name notebook --rm -p 8888:8888 -v <PATH_TO_REPOSITORY>:/home/jovyan/work jupyter/scipy-notebook
```

visit [localhost:8888](http://localhost:8888)

