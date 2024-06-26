# 스테인리스 판별 인공지능 모델
## 1. 프로젝트 소개

### 1-1. 프로젝트 개요
최근 뉴스에서는 스테인리스 팬 시장에서 제품의 품질을 고려할 때 중요한 304나 316등급의 스테인리스 스틸을 사용하는 것으로 광고되는 반면, 실제로는 저렴한 201 등급의 스테인리스 스틸을 사용한 제품들이 발견되는 사례가 늘어나고 있습니다. 이로 인해 소비자들은 제품의 믿을만한 품질에 대한 의구심을 품게 되었습니다.

304와 316 등급의 스테인리스 스틸은 주방용품 및 고급 가전제품에 사용되며, 그 내식성과 내구성으로 인해 인기를 끌고 있습니다. 그러나 201 등급은 니켈 함량이 낮아서 비교적 저렴하며 내식성이 떨어집니다. 이러한 이유로 201 등급을 사용한 제품은 가격이 낮지만 품질은 떨어지는 경향이 있습니다. 이러한 상황에서 소비자들은 제품의 실제 재질을 확인할 수 있는 방법에 대한 필요성을 느끼고 있습니다.

이로 인해 스테인리스 스틸 제품의 정확한 등급을 확인할 수 있는 신뢰할 수 있는 방법에 대한 필요성이 커지고 있습니다. 본 연구는 NIR(Near Infrared) 분광기를 활용하여 스테인리스 스틸의 등급을 정확하게 분류할 수 있는 모델을 개발하고자 합니다. NIR 분광기는 재료의 화학적 성분을 신속하게 분석할 수 있는 비파괴 검사 방법으로, 이를 통해 현장에서 바로 사용할 수 있는 장점이 있습니다. 본 연구는 NIR 분광기를 이용한 스테인리스 스틸 등급 분류 모델을 개발하여, 소비자들이 더욱 안전하고 신뢰할 수 있는 제품을 선택할 수 있도록 기여하고자 합니다.

### 1-2. 프로젝트 목표
본 연구의 목표는 NIR(Near Infrared) 분광기를 활용하여 스테인리스 스틸의 등급을 정확하게 분류하는 모델을 개발하는 것입니다. 이를 통해 소비자들이 제품의 실제 재질을 파악하고 품질을 평가하는 데 도움이 되며 신뢰할 수 있는 방법을 제공할 수 있습니다. 또한, 이 모델은 제조업체들이 스테인리스 스틸 제품의 등급을 검증하는 데에도 활용될 수 있습니다. 따라서 이 연구는 소비자들의 안전과 신뢰를 증진시키는 데 기여하고, 스테인리스 스틸 제품 시장의 투명성을 높이는 데 도움이 될 것으로 기대됩니다.

### 1-3. 프로젝트 주요 내용
스테인리스의 종류를 구분하는 인공지능 모델 개발은 다음과 같이 수행된다.

- 첫 번째는 스테인리스 201, 304, 316, 430 데이터를 모은다.
- 두 번째는 모은 4가지 데이터를 인공지능 모델을 선정하고, 학습을 시킨다.
- 세 번째는 학습된 모델에 새로운 데이터를 넣어 분류를 진행한다.

## 2. 파일 구성 및 활동 내용
주 활동 내용은 다음과 같으며, 각 활동에 대한 자세한 내용은 각각의 폴더에 있는 README.md 파일을 참고한다.

1. 주제 선정 배경

2. 스테인리스 가격비교

3. LinkSquare NIR 분광기 소개

4. 스테인리스 데이터 수집 및 전처리

5. 모델 제작 과정

6. 결론 및 기대 효과
