Deep Knockoffs
==============

This repository provides a Python package for sampling approximate
model-X knockoffs using deep generative models.

To learn more about the algorithm implemented in this package, visit  https://web.stanford.edu/group/candes/deep-knockoffs/ and read the accompanying paper.

To learn more about the broader framework of knockoffs, visit https://web.stanford.edu/group/candes/knockoffs/.

## Software dependencies

- numpy=1.14.0
- scipy=1.0.0
- pytorch=0.4.1
- cvxpy=1.0.10
- cvxopt=1.2.0
- pandas=0.23.4

## Installation guide

```bash
cd DeepKnockoffs
python setup.py install --user
```

## Examples

 - `examples/toy-example.ipynb` A usage example on a toy problem with multivariate Gaussian variables is available in the form of a 
 Jupyter Notebook.
 - `examples/experiments-1.ipynb` Code to train the machine used in the paper.
 - `examples/experiments-2.ipynb` Code to compute the goodness-of-fit diagnostics for the machine used in the paper.
 - `examples/experiments-3.ipynb` Code to perform the controlled variable selection experiments in the paper.

## License

This software is distributed under the [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.en.html) and it comes with ABSOLUTELY NO WARRANT.Y
