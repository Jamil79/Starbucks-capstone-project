# Starbucks-capstone-project
This data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.

Not all users receive the same offer, and that is the challenge to solve with this data set.

libraries used

import pandas as pd

import numpy as np

import math

import json

from datetime import datetime

from time import time

import matplotlib.pyplot as plt

import seaborn as sns

import warnings

from sklearn.naive_bayes import GaussianNB

from sklearn.ensemble import AdaBoostClassifier

from sklearn.metrics import accuracy_score,f1_score

from sklearn.model_selection import train_test_split,GridSearchCV

from sklearn.naive_bayes import GaussianNB

from sklearn.neighbors import KNeighborsClassifier

from sklearn.svm import SVC

Motivation
This project to complete udacity Data Scientist Nanodegree capstone project I've chosen Starbucks data that mimics customer behavior on the Starbucks rewards mobile app, and build a model to predict the preferred offer by the clients

Summary

the highest of all models here was SVC by (0.89) for discount offer training

the lowest of all models here was KNeighborsClassifier Model by (0.60) for bogo training

the company should focus to give more interesting offers to males since their income is higher

Discount and BOGO increase the customer buy rating
