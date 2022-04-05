### 이토록 쉬운 머신러닝&딥러닝 입문 with 사이킷런 + 파이토치 실습 코드
> 이 저장소는 <b>이토록 쉬운 머신러닝&딥러닝 입문 with 사이킷런 + 파이토치</b> (홍승백 저, 루비페이퍼 출판사, 2021년 8월 20일 출간)의 실습 코드를 제공합니다.
- 본 책은 python 3.7, torch 1.9.0, torchvision 0.10.0, torchtext 0.10.0 버전을 기준으로 작성되었습니다.
- 책 관련 문의사항은 baek2sm@naver.com 으로 메일주시면 답변드리겠습니다.
- 잘못된 내용이 없도록 원고의 내용을 수차례 검토했으나, 미처 남아있는 오류는 [정오표](/ERRATA.md)의 내용을 참고해 주세요. 학습에 불편을 드려 진심으로 사과의 말씀을 드립니다.
- 책 구매 링크: [교보문고](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&linkClass=&barcode=9791186710692) / [YES24](http://www.yes24.com/Product/Goods/103412517) / [알라딘](https://www.aladin.co.kr/shop/wproduct.aspx?ISBN=K932734583&start=pnaver_02)
<hr>

### 1. 처음 시작하는 인공지능 프로젝트
#### 1.1 인공지능 이해하기
- 1.1.1 인공지능의 종류
- 1.1.2 지도학습, 비지도 학습, 강화 학습
#### 1.2 머신러닝으로 붓꽃 품종 분류하기
- 1.2.1 프로젝트의 목
- 1.2.2 실습 환경
- 1.2.3 데이터 살펴보기 ([1.2.3.ipynb](/Part%201/1.2.3.ipynb))
- 1.2.4 K-최근접 이웃 이해하기
- 1.2.5 처음 만드는 머신러닝 모델 ([1.2.5.ipynb](/Part%201/1.2.5.ipynb))
- 1.2.6 프로젝트 개선하기 ([1.2.6.ipynb](/Part%201/1.2.6.ipynb))
#### 1.3 핵심 라이브러리 익히기
- 1.3.1 넘파이
- 1.3.2 판다스
- 1.3.3 맷플롯립 ([1.3.3.ipynb](/Part%201/1.3.3.ipynb))

### 2. 사이킷런을 활용한 머신러닝
#### 2.1 지도 학습 알고리즘
- 2.1.1 분류와 회귀 ([2.1.1.ipynb](/Part%202/2.1.1.ipynb))
- 2.1.2 선형 회귀 ([2.1.2.ipynb](/Part%202/2.1.2.ipynb))
- 2.1.3 로지스틱 회귀 ([2.1.3-1.ipynb](/Part%202/2.1.3-1.ipynb) / [2.1.3-2.ipynb](/Part%202/2.1.3-2.ipynb))
- 2.1.4 서포트 벡터 머신 ([2.1.4-1.ipynb](/Part%202/2.1.4-1.ipynb) / [2.1.4-2.ipynb](/Part%202/2.1.4-2.ipynb))
- 2.1.5 결정 트리 ([2.1.5-1.ipynb](/Part%202/2.1.5-1.ipynb) / [2.1.5-2.ipynb](/Part%202/2.1.5-2.ipynb))
- 2.1.6 나이브 베이즈 분류 ([2.1.6.ipynb](/Part%202/2.1.6.ipynb))
- 2.1.7 요약
#### 2.2 비지도 학습 알고리즘
- 2.2.1 특성 추출 ([2.2.1.ipynb](/Part%202/2.2.1.ipynb))
- 2.2.2 클러스터링 ([2.2.2.ipynb](/Part%202/2.2.2.ipynb))
#### 2.3 더 나은 모델 만들기
- 2.3.1 모델 성능 평가하기 ([2.3.1-1.ipynb](/Part%202/2.3.1-1.ipynb) / [2.3.1-2.ipynb](/Part%202/2.3.1-2.ipynb))
- 2.3.2 최적의 하이퍼파라미터 찾기 ([2.3.2.ipynb](/Part%202/2.3.2.ipynb))
- 2.3.3 파이프라인 구성하기 ([2.3.3.ipynb](/Part%202/2.3.3.ipynb))
- 2.3.4 여러 모델 결합하기 ([2.3.4.ipynb](/Part%202/2.3.4.ipynb))
- 2.3.5 모델 저장하고 불러오기 ([2.3.5.ipynb](/Part%202/2.3.5.ipynb))

### 3. 파이토치를 활용한 딥러닝
#### 3.1 딥러닝의 원리
- 3.1.1 인공 신경망과 퍼셉트론
- 3.1.2 심층 신경망
#### 3.2 파이토치 시작하기
- 3.2.1 선형 회귀 ([3.2.1.ipynb](/Part%203/3.2.1.ipynb))
- 3.2.2 로지스틱 회귀 ([3.2.2.ipynb](/Part%203/3.2.2.ipynb))
- 3.2.3 클래스로 모델 정의하기
- 3.2.4 배치 학습 ([3.2.4.ipynb](/Part%203/3.2.4.ipynb))
- 3.2.5 모델 저장하고 불러오기 ([3.2.5.ipynb](/Part%203/3.2.5.ipynb))
#### 3.3 전결합 신경망
- 3.3.1 손글씨 이미지 분류하기 ([3.3.1.ipynb](/Part%203/3.3.1.ipynb))
- 3.3.2 과적합 줄이기
#### 3.4 합성곱 신경망
- 3.4.1 합성곱 신경망의 개념 ([3.4.1.ipynb](/Part%203/3.4.1.ipynb))
- 3.4.2 합성곱 신경망 분석하기
- 3.4.3 이미지 분류 실전 프로젝트 ([3.4.3.ipynb](/Part%203/3.4.3.ipynb))
#### 3.5 순환 신경망
- 3.5.1 순환 신경망의 이해
- 3.5.2 RNN 실습 ([3.5.2.ipynb](/Part%203/3.5.2.ipynb))
- 3.5.3 LSTM 실습 ([3.5.3.ipynb](/Part%203/3.5.3.ipynb))

### 4. 데이터 다루기
#### 4.1 수치 데이터
- 4.1.1 데이터 범위 조정하기 ([예제](/Part%204/4.1.1.ipynb))
- 4.1.2 누락된 값 다루기 ([예제1](/Part%204/4.1.2-1.ipynb) / [예제2](/Part%204/4.1.2-2.ipynb) / [예제3](/Part%204/4.1.2-3.ipynb))
#### 4.2 문자열 데이터
- 4.2.1 토큰화 ([예제](/Part%204/4.2.1.ipynb))
- 4.2.2 정규 표현식 ([예제](/Part%204/4.2.2.ipynb))
#### 4.3 이미지 데이터
- 4.3.1 이미지 불러오기 ([예제1](/Part%204/4.3.1-1.ipynb) / [예제2](/Part%204/4.3.1-2.ipynb))
- 4.3.2 이미지 크기 바꾸기 ([예제](/Part%204/4.3.2.ipynb))
- 4.3.3 이미지 자르기 ([예제](/Part%204/4.3.3.ipynb))
- 4.3.4 이미지 저장하기 ([예제](/Part%204/4.3.4.ipynb))
