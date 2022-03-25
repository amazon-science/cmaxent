# Causal Maximum Entropy (CMAXENT) in Python

This module implements a set of functions to perform MAXENT from a causal perspective.

## Usage
The code here can be used to reproduce the results in the publication **Obtaining Causal Information by Merging Datasets with MAXENT**. The parts of the plots using KCI are, unfortunately, not available. To reproduce the results in the article create a python 3.6+ environment, pip install all the `requirements.txt` file and export the cmaxent folder to your python path (when the environment is activated) in your command line, like this: 

`export PYTHONPATH="/directions/to/the/folder/cmaxent"`

Finally, you should make sure that there is a `results` folder inside the `experiments` folder. Then you can reproduce all the results as easy as running the individual experiment files. For example, for the ROC curves, you can run in your command line:

`python3 ./experiments/polynomial_experiment.py`

## Reference
If you use this code in your own research, please cite our paper

```
@article{garrido2022obtaining,
  title={Obtaining causal information by merging datasets with MAXENT},
  author={{Garrido Mejia} {Sergio Hernan} and Kirschbaum Elke and Janzing Dominik},
  journal={International Conference on Artificial Intelligence and Statistics},
  pages={tba},
  year={2022},
  organizartion={PMLR}
}
```

## Further reading:
If you are interested in the origins of our work, we recommend the following readings, in addition to our AISTATS article:

From a non-causal perspective:
- E.T. Jaynes (1957) Information theory and statistical mechanics: https://bayes.wustl.edu/etj/articles/theory.1.pdf
- Wainwright and Jordan (2008) Graphical Models, Exponential Families, and Variational Inference: https://people.eecs.berkeley.edu/~wainwrig/Papers/WaiJor08_FTML.pdf


From a causal perspective:
- Sun et.al. (2005) Causal inference by choosing graphs with most plausible Markov kernels: http://is.tuebingen.mpg.de/fileadmin/user_upload/files/publications/AIMath2006-Sun_[0].pdf
- Janzing et.al. (2009) Distinguishing Cause and Effect via Second Order Exponential Models: https://arxiv.org/pdf/0910.5561.pdf
## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This project is licensed under the Apache-2.0 License.

