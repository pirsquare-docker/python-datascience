# python-datascience
Python's datascience libraries like scipy/scikit-learn/pandas takes way too long to build from scratch. Why not simply write a dockerfile to run automated builds on dockerhub. This way you can easily fetch pre-built images directly.

## Installation

    docker pull pirsquare/python-datascience

## Base Image
pirsquare/python-common


## Details
- Numpy 1.9.1
- Scipy 0.15.1
- Scikit Learn 0.15.2
- Pandas 0.15.2

