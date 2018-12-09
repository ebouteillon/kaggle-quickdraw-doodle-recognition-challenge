# Quick, Draw! Doodle Recognition Challenge

PLEASE READ MY BLOG POST : https://medium.com/@bouteillon1981/10-lessons-learned-from-participating-to-google-ai-challenge-268b4aa87efa

## Overview

This repository contains samples code I used for the "[Quick, Draw! Doodle Recognition Challenge](https://www.kaggle.com/c/quickdraw-doodle-recognition)" hosted by Kaggle, sponsored by [Google AI](https://ai.google/research).

Challenge ended on December 4th, 2018. My team and I end up in 46th position in this competition. I really want to thank all my teammates, it won't have been possible without them!

Here is our team for this challenge:

- [ebouteillon](https://www.kaggle.com/ebouteillon) (myself, charmed team leader)
- [phun](https://www.kaggle.com/phmagic) (team's blending alchemist)
- [kalili](https://www.kaggle.com/kalili) (team's deep model wizard)
- [YIANG](https://www.kaggle.com/peterzheng) (team's machine learning magician)


This repository contains only a portion of the code I wrote for this competition, my teammates are absolutely *not* responsible for my awful and buggy code.

Portion of this code is inspired by great Kagglers sharing their insight and code in Kaggle kernels and forums. I hope I did not forget to mention one of them where credit are due.


## Content of this repository

It contains three Jupyter Notebooks:

- [1-concat-csvs-into-sqlite](1-concat-csvs-into-sqlite.ipynb): prepare dataset and convert it into a single sqlite database.
- [2-training-resnet18-from-scratch-with-128px-images](2-training-resnet18-from-scratch-with-128px-images.ipynb): Train a resnet18 model using fastai library on the full dataset with square pictures of size 128px.
- a README, that you are reading now :smile:

## Hardware used

- CPU: i7-4790K
- GPU: rtx2080ti
- RAM: 24GB
