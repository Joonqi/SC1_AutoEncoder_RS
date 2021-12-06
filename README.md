# AutoEncoder Recommender System

[AutoEncoderRS](https://www.notion.so/SC1-AutoEncoderRS-cacc1ea89c8248dcb2cf0e867a3f7e6c)

Movielens에 등록된 영화 리뷰 데이터를 기반으로 개인별 영화 평점을 추정합니다. 1995년 ~ 2015년 수집된 138493명의 유저가 465564개의 영화에 남긴 20000263개의 평점 데이터를 바탕으로 분석을 진행했습니다.

Data source : [🔗Kaggle MovieLens 20M Dataset](https://www.kaggle.com/grouplens/movielens-20m-dataset) 

- Surprise 라이브러리를 이용한 ALS, SVD 모델
- Pytorch를 이용한 AutoEncoder 추천시스템 구현
- 최종모델 평균오차 RMSE 0.81
