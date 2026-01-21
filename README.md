Next Location Prediction Using GPS Trajectory Data

Overview

This repository contains the implementation and evaluation of multiple models for next-location prediction using historical GPS trajectory data. The study focuses on analysing and comparing probabilistic, machine learning, graph-based, and hybrid approaches using the Microsoft GeoLife dataset.

The goal is to understand how different modelling strategies capture sequential movement patterns, spatial relationships, and uncertainty in real-world urban mobility data.

___________________________________________

Dataset

Microsoft GeoLife GPS Trajectory Dataset

Contains real-world GPS trajectories collected over multiple years

Includes latitude, longitude, timestamp, and movement information

Analysis is limited to urban and semi-urban mobility patterns

_________________________________________________

Models Implemented

K-Nearest Neighbours (KNN) – trajectory similarity-based baseline

Extreme Gradient Boosting (XGBoost) – feature-based machine learning model

Markov Model – probabilistic sequential model

Hidden Markov Model (HMM) – temporal state-based probabilistic model

Graph Neural Network (GNN) – spatial connectivity-based model

Fusion Model (HMM + GNN) – hybrid model combining temporal and spatial learning

Preprocessing Steps

Noise and duplicate removal

Trajectory segmentation using sliding window technique

Location discretisation and encoding

Feature extraction (distance, speed, temporal information)

____________________________________________________________

Evaluation Metrics

Accuracy

Precision

Recall

Top-1, Top-3, and Top-5 Accuracy

Mean Prediction Distance (MPD)

These metrics allow evaluation of both prediction correctness and spatial realism.
