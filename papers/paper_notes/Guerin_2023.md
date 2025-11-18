# Revisiting the Cox and Munk wave-slope statistics using IASI observations of the sea surface

**C.-A. Guerin et al. (2023), Remote Sensing of Environment**

**Created:** 2025-11-13 / **Updated:** 2025-11-13  
**Keywords:** #keyword1 #keyword2 #keyword3  

---
## 체크리스트
- **Day 1**: 초록/서론/결론 + 주요 그림들, 스킴 파악 (Section 1, 2)  
- **Day 2**: 핵심 수식·모델 및 방법론 정독 (Section 2, 3)  
- **Day 3**: 결과·논의 내용 분석 (Section 4, 5, 6)  

---

## 1. 개요
이 논문은 IASI의 적외선 채널 관측을 활용해서 물리적 접근을 기반으로 **해수면 파동 경사의 확률 분포**를 결정하는 연구를 수행했다. 선행 연구인 Cox and Munk (1954, CM)에서는 이러한 확률 분포를 Gram-Charlier 방법으로 표현하였으며, 이 논문에서는 확률 분포의 7개 파라미터를 보다 물리적인 방식으로 정확하게 산출하였다. 파동 경사와 관련된 mean square slope, kurtosis, skewness 등의 풍속에 대한 관계를 정량적으로 밝혔으며, 일부는 CM과 일치하지만 다른 부분은 CM과 다르거나 보다 정확하게 밝혀냈다. 다만 이 확률 분포는 풍속만으로 결정되지는 않는 것으로 보이며, 다른 대기 해양 변수에 대한 후속 연구가 필요할 수 있다.

---

## 2. 핵심 방법론
- IASI 관측 자료 활용: 해당 대역에서 지구복사를 무시할 수 없지만, 장기간 보정이 일관적으로 잘 이루어진 센서이며, 대기 중 입자(에어로졸)에 의한 영향이 적다.
- IASI 관측 복사와 Forward model (식 1)로부터 구한 모의 복사를 이용해 least-square 방법(식 2)을 구성할 수 있고, 이로부터 해수면 온도와 파동 경사 확률의 2개 변수를 산출한다.
- 각 풍속 bin (0.5 m/s 구간)에 대해 파동 경사 확률의 cosine azimuthal series를 세울 수 있다(식 5). 이 series의 symmetric 부분을 이용해서 kurtosis 계수 $C_{40}$, $C_{04}$, $C_{22}$를 추정하고(식 21), 또 mss를 추정할 수 있다(식 18, 20). 한편 이 series의 asymmetric 부분을 이용해서 skewness 계수 $C_{12}$, $C_{30}$을 추정한다(식 24). 각 풍속 구간별 계수는 표 1에 제시되어 있다.

---

## 3. 결과 및 논의 (활용 포인트)
- 

---

## 4. 같이보기
- 이 Wiki 내부의 주제
  - [[../topics/two_scale/overview.md]]  
  - [[../topics/surface_roughness/overview.md]]  
  - [[../topics/dielectric/overview.md]]  
  - [[../topics/RTM/overview.md]]  

- 관련 논문
  - 
