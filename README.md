# tsfm
Public notebooks and utilities for working with Time Series Foundation Models (TSFM)

The core TSFM time series models have been made available on Hugging Face -- details can be found 
[here](wiki.md).


# Python Version
The current Python versions supported are 3.9 and 3.10.

## Initial Setup
First clone the repository:
```bash
git clone git@github.com:IBM/tsfm.git
cd tsfm
```

## Notebooks Installation
Several notebooks are provided in the `notebooks` folder. The allow you to perform pre-training and finetuning on the models.
To install use `pip`:

```bash
pip install ".[notebooks]"
```

## Demos Installation
The demo presented at NeurIPS 2023 is available in `tsfmhfdemos`. This demo requires you to have pre-trained and fine-tuned models in place (we plan to release these at later date). To install the requirements use `pip`:

```bash
pip install ".[demos]"
```


## Issues
If you encounter an issue with this project, you are welcome to submit a [bug report](https://github.com/IBM/TSFM/issues).
Before opening a new issue, please search for similar issues. It's possible that someone has already reported it.


# Notice

The intention of this repository is to make it easier to use and demonstrate IBM Research TSFM components that have been made available in the [Hugging Face transformers library](https://huggingface.co/docs/transformers/main/en/index). As we continute to develop these capabilities we will update the code here.


IBM Public Repository Disclosure: All content in this repository including code has been provided by IBM under the associated open source software license and IBM is under no obligation to provide enhancements, updates, or support. IBM developers produced this code as an open source project (not as an IBM product), and IBM makes no assertions as to the level of quality nor security, and will not be maintaining this code going forward.