# "으뜸 머신러닝" 저장소 소개
## 프로그램 코드와 자료를 제공합니다.

안녕하세요 독자여러분 이곳은 생능출판사의 책 "으뜸 머신러닝"(2021년 7월 출간) 관련 저장소입니다. 이 책의 소스코드와 주피터 노트북 파일, colab 주소, 정오표등 다양한 자료와 정보가 있는 곳입니다.

이 책 "으뜸 머신러닝"은 머신러닝을 처음 배우는 입문자와 머신 러닝의 개념을 익힌 상태에서 텐서플로우를 이용한 본격적 개발을 시작하려는 분들을 위한 책입니다.

 * [[YES24]](http://www.yes24.com/Product/Goods/102577953), [[인터파크]](http://book.interpark.com/product/BookDisplay.do?_method=detail&sc.shopNo=0000400000&sc.prdNo=352099030&sc.saNo=003002001&bid1=search&bid2=product&bid3=title&bid4=001), [[교보문고]](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788970504919&orderClick=LEa&Kc=)
<p align="center">
  <img src="image/PrimeML_cover.png" width=350px>
</p>

# 책의 소스코드(colab 주소, .py 파일, ipynb 파일)
* [소스코드](https://github.com/dknife/ML/tree/main/Source/README.md)
: "으뜸 머신러닝" 책의 장별 소스코드가 .ipynb, colab 페이지를 통해서 제공됩니다

## 함께 보면 좋은 책

이 책을 읽기 위해 파이썬과 데이터 다루기와 관련된 저자들의 이전 책을 함께 보면 좋습니다. 

* 으뜸 파이썬, 박동규, 강영민, 생능출판사 (2020) - 세종도서 학술부문 선정
 * [[YES24]](http://www.yes24.com/Product/Goods/89140722), [[인터파크]](http://book.interpark.com/product/BookDisplay.do?_method=detail&sc.shopNo=0000400000&sc.prdNo=330274507&pis1=book&pis2=product), [[교보문고]](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788970503691&orderClick=LEa&Kc=)

* (따라하며 배우는) 파이썬과 데이터 과학, 천인국, 박동규, 강영민, 생능출판사 (2020)
 * [[YES24]](http://www.yes24.com/Product/Goods/96555988), [[인터파크]](http://book.interpark.com/product/BookDisplay.do?_method=detail&sc.shopNo=0000400000&sc.prdNo=345271510&sc.saNo=003002001&bid1=search&bid2=product&bid3=title&bid4=001), [[교보문고]](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788970504773&orderClick=LEa&Kc=) 
<p align="center">
  <img src="image/20BFF5E5-1B47-490E-99A4-6A76440B6F2C.png" width=200px>
  <img src="image/BB56B4F0-484E-4B5E-8649-EA827AF9271B.jpeg" width=200px>
</p>


*** 
# 정오표

실수는 인간적이지만, 실수를 고집하는 것은 악마적이다 (Errare humanum est, perseverare autem diabolicum)

### 오류를 줄이기 위해 노력했으나, 죄송하게도 오류가 남았습니다. 판을 바꿀 때마다 지속적으로 수정하도록 하겠습니다. 아직 고치지 못하고 남은 오류와 수정 내용을 공유합니다. 
## 1판 1쇄
[[1판 1쇄 정오표]](https://docs.google.com/document/d/1V74pmmTYCMnNvadaa2z0zNh1vITWZ8w91YRRSG5wVw0/edit?usp=sharing) <- 클릭하세요
* 오류신고 : ymkang@tu.ac.kr 로 메일 보내주시면 됩니다.

***
# 책의 목차

## Chapter 01 : 머신러닝이란
##### 1.1 인간을 닮은 기계를 만들기 위한 노력 : 그 시작
##### 1.2 생각하기 시작하는 기계
##### 1.3 반복되는 사계절: 추운 겨울을 이기고 다시 찾아온 인공지능의 봄
##### 1.4 머신러닝은 무엇을 하려는 것인가?
##### 1.5 우리가 다룰 머신러닝이 정확히 무엇이며 어떤 것이 있는가
##### 1.6 머신러닝, 무엇이 문제일까?

## Chapter 02 : 머신러닝을 위한 기초지식
##### 2.1 수학 표기
##### 2.2 벡터와 행렬
##### 2.3 벡터와 행렬의 기본 연산
##### 2.4 미분과 기울기, 그리고 경사하강법의 개념
##### 2.5 편미분과 기울기
##### 2.6 모델, 파라미터, 그리고 학습
##### 2.7 오차의 기울기를 이용한 학습의 기본 원리와 최적해
##### 2.8 과적합, 과소적합, 그리고 일반화
##### 2.9 과적합을 피하기 위한 방법들

## Chapter 03 : 구현을 위한 도구
##### 3.1 파이썬
##### 3.2 구글 코래버러토리를 이용한 프로그래밍
##### 3.3 구글 드라이버의 내용을 코래버러토리에서 이용하기
##### 3.4 넘파이는 머신러닝을 위한 데이터 처리의 핵심 도구
##### 3.5 넘파이 활용의 기본 - 브로드캐스팅, 인덱싱, 슬라이싱
##### 3.6 벡터화 연산 - 넘파이 배열 계산 성능의 핵심
##### 3.7 논리 인덱싱으로 빠르게 데이터 추려내기
##### 3.8 판다스 소개
##### 3.9 판다스로 데이터 읽고 확인하기
##### 3.10 데이터 시리즈 선택하여 시각화해 보기
##### 3.11 편리한 데이터 다루기 - 슬라이싱과 열 데이터 추가
##### 3.12 판다스를 이용한 데이터 분석
##### 3.13 데이터 정제와 결손값의 처리
##### 3.14 그룹핑과 필터링
##### 3.15 데이터 구조의 변경: pivot과 concat
##### 3.16 데이터의 병합: merge

## Chapter 04 : 선형 회귀로 이해하는 지도학습
##### 4.1 회귀 모델
##### 4.2 선형회귀와 지도학습
##### 4.3 실제 데이터를 읽고 가설 만들어 보기
##### 4.4 좋은 가설과 모델의 오차
##### 4.5 데이터의 관계를 설명하는 선형회귀 함수의 시각적 이해
##### 4.6 오차의 종류에 따른 오차 곡면의 모습
##### 4.7 오차로 가설을 평가하고 좋은 가설 찾기
##### 4.8 기계 학습의 개념으로 해석하는 선형회귀
##### 4.9 Scikit-Learn을 이용한 선형 회귀
##### 4.10 다변량 회귀분석 - 수학적 모델
##### 4.11 회귀분석의 학습, 혹은 최적화 방법 - 정규 방정식
##### 4.12 정규 방정식의 유도와 시간 복잡도
##### 4.13 다변량 선형 회귀 분석을 위한 데이터 확보하기
##### 4.14 다변량 데이터 특징들 사이의 상관 관계를 파악하기
##### 4.15 특징들의 상관 쌍 그림을 확인하고 중요 특징 추출하기
##### 4.16 다변량 선형 회귀에 사용할 데이터를 훈련용과 검증용으로 분리하기
##### 4.17 데이터의 정규화를 통한 분석 성능 개선하기
##### 4.18 데이터의 표준화를 통한 분석 성능 개선하기

## Chapter 05 : 분류와 군집화로 이해하는 지도 학습과 비지도 학습
##### 5.1 k-NN 알고리즘과 분류문제
##### 5.2 k-NN 알고리즘을 위한 데이터 준비하기
##### 5.3 k-NN 분류기를 실행하자
##### 5.4 k-NN 활용 예제 - 붓꽃 데이터 준비하기
##### 5.5 k-NN 활용 예제 - 붓꽃 데이터로 학습하기
##### 5.6 새로운 꽃에 대해서 모델을 적용하고 분류해 보자
##### 5.7 표집 편향과 성능 측정을 위한 평가지표
##### 5.8 사이킷 런의 성능지표 함수들
##### 5.9 앙상블 - 머신러닝의 민주주의
##### 5.10 군집화의 개념과 비지도 학습
##### 5.11 k-평균 알고리즘 살펴보기
##### 5.12 k-평균 알고리즘과 k-NN 알고리즘의 비교: 지도 학습과 비지도 학습
#### LAB5-1 k-평균 알고리즘과 k-NN 알고리즘의 비교 : 지도 학습과 비지도 학습
#### 5장 미니 프로젝트 A1 잡음제거: k-NN의 활용

## Chapter 06 : 다양한 머신러닝 기법들 다항 회귀, 결정 트리, SVM
##### 6.1 다항 회귀
##### 6.2 다항 회귀의 문제점 - 과적합, 그리고 폭발적인 복잡도 증가
##### 6.3 과적합과 과소적합 - 공짜 점심은 없다
#### LAB6-1 다항회귀의 회귀 함수를 그려 보자
##### 6.4 결정 트리를 이용한 분류
##### 6.5 어떤 속성이 가장 중요한가?
##### 6.6 결정 트리 분할의 기준 - 정보량과 불순도
##### 6.7 결정 트리를 손으로 만들어 보자 - ID3 알고리즘
##### 6.8 지니 불순도를 이용한 효율적인 평가 - CART 알고리즘
##### 6.9 사이킷런의 결정 트리로 붓꽃 분류하기
#### LAB6-2 꽃받침의 너비와 길이로 결정트리를 만들자
#### LAB6-3 엔트로피를 이용하여 결정 트리 만들기
##### 6.10 SVM - 서포트 벡터 머신의 소개
##### 6.11 하드 마진 서포트 벡터 머신의 구현
##### 6.12 소프트 마진 서포트 벡터 머신의 구현
##### 6.13 사이킷런을 이용한 서포트 벡터 머신 사용하기
##### 6.14 파이프라인을 이용한 데이터 정제
##### 6.15 다항 특정 변환을 통한 비선형 서포트 벡터 머신의 구현
#### LAB6-4 비선형 SVM을 이용한 데이터 분류
##### 6.16 커널 트릭을 이용한 비선형 서포트 벡터 머신
#### LAB6-5 커널 트릭을 이용한 비선형 SVM
#### 6장 미니 프로젝트 B1 얼굴 찾기: SVM으로 분류하기

## Chapter 07 : 인공 신경망 기초 - 문제와 돌파구
##### 7.1 뇌의 동작을 흉내내자 - 연결주의자의 목표
##### 7.2 학습할 수 있는 신경 모델 - 퍼셉트론
#### LAB7-1 AND / OR 연산을 수행하는 퍼셉트론
##### 7.3 학습의 원리 - 연결 강도의 변경
#### LAB7-2 논리합을 수행하는 퍼셉트론 만들기
#### LAB7-3 다양한 논리 연산이 가능하게 퍼셉트론 훈련하기
##### 7.4 퍼셉트론, 연결주의가 누린 첫 영예와 긴 좌절
##### 7.5 퍼셉트론이 XOR 문제를 풀 수 있게 만드는 방법
#### LAB7-4 입력 다항화로 XOR를 해결해 보기
##### 7.6 다층 퍼셉트론의 학습 - 오차를 줄이도록 연결 강도를 고치자
##### 7.7 다층 퍼셉트론의 학습 - 오차를 아래로 전파하자
##### 7.8 역전파 알고리즘에 대한 직관적 이해
##### 7.9 계층 단위로 신호 전파하기
##### 7.10 역전파 알고리즘의 요약
#### LAB7-5 XOR 연산이 가능한 다층 퍼셉트론 만들기
#### LAB7-6 다층 퍼셉트론으로 비선형 회귀 구현하기
##### 7.11 신경망을 설계하고 훈련을 실시할 수 있는 도구 : 텐서플로우

## Chapter 08 : 고급 인공 신경망 구현
##### 8.1 심층 신경망이 부딪힌 한계 - 사라지는 기울기
##### 8.2 심층 신경망 학습의 돌파구 - 연결강도 초기화
##### 8.3 활성화 함수의 다양화
##### 8.4 최적화 기법 - 경사하강법의 문제와 개선
##### 8.5 다양한 최적화 기법 소개
##### 8.6 텐서플로우 소개
##### 8.7 텐서플로우로 시작하는 Hello world! - MNIST 예제
##### 8.8 keras로 순차 심층신경망 구축하기
##### 8.9 인공 신경망을 최적화 시키자
##### 8.10 부드러운 최대값: 소프트맥스 함수
##### 8.11 원-핫 인코딩과 평균제곱 오차
##### 8.12 평균제곱 오차와 교차 엔트로피 오차
##### 8.13 정규화와 표준화
##### 8.14 배치 경사 하강법, 확률적 경사 하강법, 미니 배치 경사 하강법
##### 8.15 더 깊은 층으로 정확도를 높여보고 교차검증도 하자
##### 8.16 학습데이터에만 최적화된 신경망 개선하기 : 드롭아웃
#### LAB8-1 Fashion-MNIST 데이터 분류하기

## Chapter 09 : 신경망 부흥의 시작, 합성곱 신경망
##### 9.1 시각 정보 처리와 합성곱의 필요성
##### 9.2 합성곱의 기본 개념 이해
##### 9.3 합성곱을 통한 특징 추출
##### 9.4 합성곱 수행 신경망의 기본 구조와 문제
##### 9.5 패딩, 스트라이딩, 다중 채널
##### 9.6 강건한 모델을 만드는 풀링
#### LAB9-1 합성곱을 만들어보자
##### 9.7 합성곱 신경망 모델의 구성
##### 9.8 합성곱 신경망 모델의 성공
#### LAB9-2 합성곱 신경망으로 패션 MNIST 분류를 개선하기
#### LAB9-3 성능 좋은 CNN을 가져다 써보자
##### 9.9 전이학습 - 이미 훈련된 모델을 고쳐 쓰기
#### 9장 미니 프로젝트 B2 얼굴 찾기: CNN 활용하기
#### 9장 미니 프로젝트 B3 얼굴 찾기: 전이학습 활용하기

## Chapter 10 : 순환 신경망
##### 10.1 순환 신경망의 적용 분야
##### 10.2 순환 신경망 구조
##### 10.3 순환 신경망 셀의 구조와 유닛
##### 10.4 텐서플로를 이용하여 단순 RNN 모델 만들기
##### 10.5 RNN을 학습시켜 예측을 해 보자.
##### 10.6 RNN을 다층구조로 만들어 적은 수의 파라미터로 좋은 성능을 내자
##### 10.7 장기 의존성 문제와 RNN의 한계
##### 10.8 장기 의존성 문제를 해결하는 LSTM
##### 10.9 LSTM 셀의 각 게이트 별로 동작 살펴 보기
##### 10.10 GRU - 장기 의존성 문제를 해결하는 더 간단한 게이트들
##### 10.11 단순 RNN과 LSTM, GRU 모델의 비교 - 시퀀스 데이터 준비
##### 10.12 단순 RNN과 LSTM, GRU 모델의 비교 - 성능 비교
#### LAB10-1 비선형 시퀀스를 순환신경망으로 예측하자
#### LAB10-2 기억이 필요한 시퀀스를 예측해 보자

## Chapter 11 : 차원축소와 매니폴드 학습
##### 11.1 차원, 그리고 차원의 저주
##### 11.2 차원 축소
##### 11.3 주성분 분석과 특이값 분해
##### 11.4 특이값 분해의 기하적 이해
#### LAB11-1 3차원 공간의 데이터에서 주성분을 찾아보자
##### 11.5 커널 PCA
##### 11.6 다양한 커널의 적용
#### LAB11-2 주성분을 추출해 이미지를 압축해보자
##### 11.7 매니폴드 학습과 LLE 기법의 이해
##### 11.8 LLE 기법의 구현을 위한 최적화 해 구하기
#### LAB11-3 LLE를 넘파이로만 구현해 보자
##### 11.9 그 밖의 매니폴드 학습 알고리즘
#### LAB11-4 매니폴드 학습을 이용한 차원 축소 실습

## Chapter 12 : 오토인코더와 잠재표현 학습
##### 12.1 특징, 그리고 잠재 표현 학습
##### 12.2 압축과 복원, 잠재표현 - 오토인코더
#### LAB12-1 오토인코더 차원 축소하기
#### LAB12-2 다층 구조 오토인코더 차원 축소/복원
#### LAB12-3 오토인코더를 이용한 이미지 압축과 복원
#### 12장 미니 프로젝트 A2 잡음제거: 오토인코더 활용
#### 12장 미니 프로젝트 C1 차원축소: 데이터 분포 가시화

## Chapter 13 : 인공지능의 현재와 미래
##### 13.1 인공 신경망으로 무엇을 할 수 있을까?
##### 13.2 실시간 객체탐지를 위한 YOLO
##### 13.3 YOLO의 주요 처리 절차
##### 13.4 어텐션에 주목해 보자
##### 13.5 트랜스포머와 GPT-3
##### 13.6 적대적 생성 모델: GAN
##### 13.7 강화학습: 알파고부터 뮤제로까지
##### 13.8 인공지능과 윤리적 딜레마: 윤리적 기계

***

# 책의 LAB과 연습문제 정답지 제공에 관하여

이 책에는 많은 LAB문제와 연습문제가 제공됩니다. 저자들이 모든 문제에 대해 답을 만들어 보았지만, 이것은 문제의 유효성을 검증하기 위한 것일 뿐입니다.  
LAB과 연습문제는 답이 제시되지 않은 문제의 해답을 찾는 과정과 실습을 통해 더 깊은 학습을 할 수 있도록 준비된 것입니다.
이에 저자는 정답지 제공을 하지 않습니다.

