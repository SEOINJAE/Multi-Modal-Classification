# Multi-Modal-Classification
NLP and Image Fashion item Classification

# Classification of Fashion E-commerce Products based on Multi-modal Deep Learning and Transfer Learning Optimization Methodology

- 패션 이커머스에 최적화된 카테고리 분류 딥러닝 모델 구축
- 문제 상황
    - 폭발적으로 성장하고 있는 패션 이커머스에는 하루에도 수 만개의 상품이 등록된다.
    - 네이버의 경우 매일 2,000만개 이상의 새로운 상품이 등록되고 5,000개의 카테고리에 매칭된다.
    - 카테고리는 검색 시스템 최적화와 정확한 상품 노출을 통한 매출 증가에 중요한 역할을 한다.
    - 하지만, 판매자가 직접 카테고리를 설정하는 과정에서 잘못된 카테고리로 매칭되는 경우가 많다.
    - 수 많개의 상품을 수동으로 관리자가 올바른 카테고리로 수정하고 관리하는 것은 불가능에 가깝다.

- 해결 방안
    - 딥러닝을 활용해 카테고리 분류를 자동화 한다.

- 딥러닝 모델 구성에서의 문제점 및 해결방안

|**문제점**|**해결방안**|**내용**|
|---|---|---|
|이커머스 데이터의 특성상 극도로 데이터가 편향되어있다.|언더샘플링|일부 데이터 삭제|
|패션 이커머스 대표 이미지에는 모델이 제품과 함께 등장해 딥러닝 모델이 인식하기 힘든 어려움이 있다.|멀티모달|노이즈 영향도 줄임|
|이미지와 텍스트를 동시에 활용해 많은 데이터를 학습시 많은 컴퓨팅 자원과 시간이 소요된다.|전이학습|훈련데이터가 적어도 빠르고 정확하게 학습|




# Architecture
<!-- ![model](https://user-images.githubusercontent.com/69412493/229341127-71ec40a3-6948-41f7-9877-bd5492daa2c1.jpeg) -->


<img src="https://user-images.githubusercontent.com/69412493/229341127-71ec40a3-6948-41f7-9877-bd5492daa2c1.jpeg" width="250" height="250"/>