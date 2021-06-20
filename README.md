# Real Time Traffic Detection From Tweets

A deep learning based real-time tarffic prediction model that is used to detect the road traffic using twitter data.
 
## Modules used

### For CNN model creation

* Google Colab - (Python3, gensim, Scikit, Pandas, tensorflow, Numpy, matplotlib)

### For creating website

* django
* pandas
* datetime
* time
* tensorflow
* requests
* json
* tweepy
* numpy
* pytz
* csv
* HTML5-CSS

## Steps to run .ipynb files

* Use [Google Colab](https://colab.research.google.com/notebooks/) to run .ipynb files in the cloud.

## Steps to deploy model in local system

* Open cmd
* Create virtual environment
* Install dependencies mentioned above for django
* Change directory to the place where the code is saved(directory -> buttonpython)
* run "python3 manage.py runserver 127.0.0.1:5000". 
* Copy the local link.
* Paste it on browser to deploy locally

## Note:-

* If changes in dataset is made, model might give out undesirable outputs.
* Install all python modules mentioned above before running the project.
* tweet_final.csv gives output after prediction based on real-time  data in csv format.
