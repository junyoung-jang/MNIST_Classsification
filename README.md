﻿# MNIST_Classsification
## 프로젝트 요약

학교 수업인 기계공학을위한머신러닝 수업에서 진행한 프로젝트 입니다.
MNIST 데이터 5개가 Sequential하게 나열되어 있는 이미지를 분류하는 프로젝트 입니다

## 프로젝트 기간
2023년 12월 7일부터 12월 15일

## 멤버 소개
장준영: 연속된 데이터 분류 방법 고안, 인공신경망을 이용한 데이터 분류 모델 개발, 하이퍼파라미터 튜닝

장주원: Scikit-Learn을 이용하여 SVM 모델을 이용하여 데이터 분류, 하이퍼파라미터 튜닝

최지호: 기존에 사용된 MNIST 분류모델 조사, 하이퍼파라미터 튜닝

## 환경 및 라이브러리

Python

Google Colaboratory

Numpy, Pandas: 데이터 로드 및 행렬 계산을 하기위해 사용하였습니다

PIL: 이미지 파일을 로드 하고 Array로 변경, 이미지 회전 및 플립핑을 하기 위해 사용하였습니다

Matplotlib.pyplot: 이미지를 로드하기 위해 사용하였습니다

## Sequential하게 나열된 데이터 분류법

Sequential하게 나열된 데이터를 하나의 이미지로 보고 학습할 경우 경우의 수가 너무 많아 학습하는데 좋지 않을 것이라 판단하였습니다.

저희는 따라서 기존의 MNIST 데이터를 이용하여 학습을 진행하되, (28, 140)데이터를 (28, 28) 5개로 분할하여 예측하고 그 결과를 합쳤습니다
