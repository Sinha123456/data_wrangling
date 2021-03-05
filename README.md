# Data Wrangling
Real world data is dirty, untidy, messy, you have to put 80% of your effort to clean the data so you can visualize and analize your data properly.

# Table of contents

## Introduction
## Requirment
## Doccumentation
## Recommended models
## Installation


# Introduction
For data wrangling process, data is gathered from three differnt resources, main data is WeRateDogs, that data That data is gathered from the Twitter page
called WeRateDog. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 
These ratings almost always have a denominator of 10. The numerators, though? 
Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers
and has received international media coverage.  Main goal of that project is to assess, clean,  analyze and visualize that data.
cloning the repository (https://github.com/Sinha123456/data_wrangling.git)


# Requirment 
Python libraries
Tweet API key
external tool like excel,or other text editor to assess your data but python libraries are best visually and programmatically assessment.
For small data these external tools are handy for assessing, cleaning your data.

# Doccumentation
For Tweet ApI key use that site: https://developer.twitter.com/en/docs/twitter-api/v1/data-dictionary/object-model/tweet
request library https://pypi.org/project/requests/2.7.0/


# Recommended models
import pandas as pd

import numpy as np

import os

import re
import requests

import tweepy

import datetime

import timeit
import matplotlib.pyplot as plt

import seaborn as sns

%matplotlib inline

import requests
from PIL import Image

from io import BytesIO

from timeit import default_timer as timer

import json

from IPython.display import IFrame

# Installation
There is no need to install any libraries separatly, These libraries are pre-installed with anaconda package.
If you are working in google colab notbook, you don't have to install anything, google colab provide you all you need.

## License & copyright
Sinha123456

Licensed under the [MIT License](License)

