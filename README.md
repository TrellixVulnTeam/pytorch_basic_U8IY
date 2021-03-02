# Pytorch 기초 

Pytorch 를 이용하여 기본 모델을 구현한 프로젝트 

## 0. 기초 코드
* 텐서 기본 조작법을 모아둔 소스 코드
* 소스 코드

    | 파일           |  설명           |
    | ---------------|:----------------------- |
    | pytorch.py     | 텐서 나눗셈, 합, 텐서 합치기 , 자동 미분    |
 

## 1. 단순 선형 회귀 
* 학습 시간에 따라 점수가 달라진다.  1시간 공부한 학생은 점수가 20점이다.
* 점수 = 공부시간 * w + b  라고 할때, w 와 b 를 매개 변수 값을 인공지능 학습을 통해 알아보자.

    | 학습 시간(y)  | 점수(x)         |
    | ----------|:------------------ |
    | 1    | 20   |
    | 2    | 40   |
    | 3    | 60   |

* 소스 코드
    | 파일           |  설명           |
    | ---------------|:----------------------- |
    | linear_regression.py     |  학습시간, 점수의 데이터가 행렬로 구성   |
    | linear_regression_vector.py     |  학습시간, 점수의 데이터가 벡터로 구성     |

## 2. 선형 회귀
* 계속 업데이트 중