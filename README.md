# BOW_transferlearning

Git repository for Niels Helsø talk held at pydatacopenhagen 28/2-2019   

**Attention**  
If you want to run any tutorial in this repo you have to download data.  
Se data  
**Attention**

## Folders

* Pictures
  * Pictures used for the presentation
* src (all scripts used)
  * data (scripts handling data)
  * model (scripts building and training models)
  * preprocessing (scripts related to preprocessing data)

## Notebooks

* bow_tutorial
  * how to build a simpel BOW model with GradientBoosting as a Classifier and save model. 
* word2vec_tutorial
  * how to build a simple word2vec model and save model.
* Fasttext_tutorial
  * how to build a fasttext model and save model.

## Data

The data used for the presentation is located here [git](https://github.com/Proteusiq/dksentimentapi/blob/master/app/data/sentiment_data).  
It is created by Prayson Wilfred Daniel and source code can be found at this repo:  
[trustpilot dansk](https://github.com/Proteusiq/dksentimentapi)  

**OBS**  
You have to download the data and place it in a folder called 'data' in order for the models to work.  
Like so:  
```bash
BOW_transferlearning  
 |  
  -data  
     |  
     -sentiment_data  
  - src
     |
     - model
     - preprocessing
     - etc
  - pictures 
```


## Articles and websites

1. [Word2Vec](https://arxiv.org/pdf/1301.3781.pdf)
2. [FastText_article](https://arxiv.org/pdf/1607.01759.pdf)
3. [FastText_web](https://fasttext.cc/)
4. [ULMFIT](http://nlp.fast.ai/classification/2018/05/15/introducting-ulmfit.html)
5. [LSTM Language Models](https://arxiv.org/pdf/1708.02182.pdf)
6. [ULMFIT_tutorial](https://www.analyticsvidhya.com/blog/2018/11/tutorial-text-classification-ulmfit-fastai-library/)

## Install

Prerequisites is to have **python 3** install on your system fx.Ubuntu.  
This guide is using **Ubuntu 18.04 bionic beaver**.  

To run all the code in this repo do the following:  

### Run the tutorials

1. Clone this repo

```bash
git clone https://github.com/slein89/BOW_transferlearning.git
```

2. cd into repo

```bash
cd BOW_transferlearning
```

3. Make a virtual environment with python 3

```bash
python3 -m venv <name of venv>
```

4. install the python requirements with pip

```bash
pip install -r requirements.txt
```

5. run the following snippet to test if your enviroment is set up correctly.  
if it fails please check that the pip run without any fails. 

```bash
python src/test_venv.py
```

6. If this run perfectly you should be apple to begin your journey.  
Now let's get some data and have fun!
Please proceed to one of the following tutorials in the github repo. 

### Build ulmfit

To run ulmfit follow this [tutorial](https://www.analyticsvidhya.com/blog/2018/11/tutorial-text-classification-ulmfit-fastai-library/) for english ulmfit  
I will publish code and weight for danish in a near furture.  