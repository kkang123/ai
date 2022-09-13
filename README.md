# 인공지능(Artificial Intelligence)

## 강의자료(pdf)
> * 머신러닝(분류): https://github.com/yungbyun/ai/blob/master/01.%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D(%EB%B6%84%EB%A5%98).pdf
> * 머신러닝(예측): https://github.com/yungbyun/ai/blob/master/02.%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D(%EC%98%88%EC%B8%A1).pdf
> * 파이썬 모듈화_기본: https://github.com/yungbyun/ai/blob/master/03.%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%AA%A8%EB%93%88%ED%99%94_%EA%B8%B0%EB%B3%B8.pdf

## 동영상 강의 (처음 7개 동영상 시청 필수)
> * 캐글(Kaggle) 소개1, https://www.youtube.com/watch?v=9GWb9yNcsvc&t=112s
> * 캐글(Kaggle) 소개2, https://www.youtube.com/watch?v=VNOYpNItpdI
> * 식물생장예측: https://youtu.be/RKXoSuwuX9I
> * 성별예측: https://www.youtube.com/watch?v=JeYj5OHwQOw
> * 실습(성별예측1): https://youtu.be/QBq2f_1gfZA 
> * 실습(성별예측2): https://youtu.be/4IEbdh62d2Y
> * 실습(식물생장예측): https://youtu.be/DZnpkKxeB-w
> * 실습(모듈화01): https://youtu.be/p6qhjnvTV0k
> * 실습(모듈화02): https://youtu.be/8dpmy2wxxsI
> * 실습(모듈화03): https://youtu.be/zEn7F80J9Ss 
> * 실습(모듈화04): https://youtu.be/YdGYkry6wI4 
> * 실습(모듈화05): https://youtu.be/kA1BcE9iMvA
> * 실습(모듈화06): https://youtu.be/r7o6UiiM1Lc 
> * 실습(모듈화07):https://youtu.be/jFzTmaH0BOI
> * 실습(모듈화08):https://youtu.be/eOiZWL2qTSQ
> * 실습(모듈화09):https://youtu.be/RuI6V-HnA1w
> * 실습(모듈화10):https://youtu.be/GuceU9CTYaQ
> * 실습(모듈화11):https://youtu.be/KzkssBLEFuw
> * 실습(모듈화12): https://youtu.be/L7CxEreBp8I

## (분류) 성별 알아맞히기
> 키/몸무게/발크기로 성별 알아맞추기 <br/>
> https://www.kaggle.com/yungbyun/female-male-classification-original (original)

## (예측) 식물 생장 예측하기
> 몇일 후 잎의 길이와 너비가 얼마나 자랄 것인지를 예측함. <br/>
> https://www.kaggle.com/yungbyun/plant-diary-original2/

## (분류) 붓꽃(Iris) 인식
> https://www.kaggle.com/ash316/ml-from-scratch-with-iris

## (예측) 집값 예측
> https://www.kaggle.com/yungbyun/house-price-prediction-for-tutorial <br/>
> https://www.kaggle.com/yungbyun/house-price-prediction-simple (조금 단순하게)

> **각 모듈에 대한 간단한 설명입니다.**
> * **Pandas 판다스 : 데이터를 읽어들이고 유지하고 관리할 수 있는 멋진 모듈 (데이터베이스에 비유)**
> * **NumPy 넘파이 : 다양한 수치연산, 변환 기능 등을 갖는 멋진 모듈 (계산기에 비유)** 
> * **Seaborn 시본 : 데이터를 멋지게 표시하는 모듈 (엑셀에 비유)**
> * **sklearn 싸이킷런 : 머신러닝 모델을 만들 수 있는 멋진 모듈 (인공지능 모델 구현)**

## Google Colab에서 구글 드라이브 파일 사용하기
```
from google.colab import drive
drive.mount('/mydrive')

import pandas as pd
df = pd.read_csv("/mydrive/My Drive/data/fulldata.csv")
df
```


