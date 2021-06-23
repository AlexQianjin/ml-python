# ml-python
Machine Learning with Python

## Run Jupyter Lab with Docker
- docker pull jupyter/tensorflow-notebook:lab-3.0.16
- docker run --name jupyter -p 8888:8888 -v "$PWD":/home/jovyan/work jupyter/tensorflow-notebook:lab-3.0.16
