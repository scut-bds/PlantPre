# [PlantPre](https://github.com/scut-bds/PlantPre)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-red.svg)](#python)  [![GitHub stars](https://img.shields.io/github/stars/scut-bds/PlantPre)](https://github.com/scut-bds/PlantPre/stargazers) [![GitHub license](https://img.shields.io/github/license/scut-bds/PlantPre)](https://github.com/scut-bds/PlantPre/blob/main/LICENSE) ![GitHub repo size](https://img.shields.io/github/repo-size/scut-bds/PlantPre) [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black) ![GitHub last commit](https://img.shields.io/github/last-commit/scut-bds/PlantPre)     

README: [English](https://github.com/scut-bds/PlantPre/blob/main/README.md) | [中文](https://github.com/scut-bds/PlantPre/blob/main/README-zh.md)   

**A Dataset for Falling Risk Assessment in the Elderly using Wearable Plantar**    




## Introduction
Falls are the leading cause of death by injury in the elderly. Falling risk assessment in daily life can prevent the elderly from falling. Building dataset for assessing falling risk in the elderly based on wearable devices has become a popular research topic, and relevant data processing methods (e.g., feature engineering/deep learning) achieved good performance. However, these datasets cannot be used in daily life space, as their data acquisition equipment is worn uncomfortably or is too expensive. Therefore, relevant data processing method based on these datasets cannot be applied to real scene in daily life, and their practical ability is limited. In order to make daily falling risk assessment possible, we propose a novel approach to construct a continuous plantar pressure dataset of 48 older adults along with each older adult's falling risk label (their Berg Scale score). Our dataset is collected by plantar pressure monitoring shoes suitable for daily living spaces. Furthermore, we applied the Conv-LSTM algorithm on our dataset, and the classification result is up to 92%, which proves that it is a dataset suitable for biomedical relationship extraction. Our dataset is helpful for balance assessment and health monitoring in the elderly. We encourage other researchers to test their own falling risk assessment methods on our dataset.
