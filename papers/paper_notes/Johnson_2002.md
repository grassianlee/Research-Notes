# Comparison of the Physical Optics and Small Slope Theories for Polarimetric Thermal Emission From the Sea Surface

**Johnson (2002), IEEE Transactions on Geoscience and Remote Sensing**

**Created:** 2026-01-05 / **Updated:** 2026-01-05  
**Keywords:** Physical Optics, Small Scale Approximation  

---

## 1. 개요
본 연구에서는 해수면의 편광 마이크로파 방출을 묘사하는 방법 중 물리광학(PO; Physical Optics)과 Small Slope Approximation의 결과를 비교한다. (전자는 해수면 파동 규모가 전자기파 파장과 유사하며 해수면 경사가 작을 때, 후자는 해수면 파동 규모가 전자기파 파장에 비해 훨씬 클 때 적용된다.) 두 이론에서 산출된 해수면 방출의 azimuthal harmonic에 대한 장파(long wave)의 기여도는 3차 항까지 잘 일치했다. 따라서 (shadowing이 적을 경우) PO 방법을 장파 계산에 적용할 수 있다. 다만 SSA가 비국소적인 효과를 일부 포함할 수 있는 반면, PO는 국소적인 근사임을 감안해야 한다.

---

## 2. 핵심 구조
- PO 모형: 프레넬 반사도로 구성된다. Shadowing effect를 고려하면 에너지 보존이 성립하지 않으므로 여기서는 이를 제외한다.
- SSA 모형: SSA 계수에 대한 적분을 테일러 전개로 단순화했다. 최종 식은 장파 함수 $h$와 surface moment (e.g., $S_x^2)의 곱으로 정의된다.
- 두 모형 모두 테일러 전개에 의해 동일한 구조를 가지므로, PO 및 SSA 방법의 장파 함수를 비교할 수 있다.

---

## 3. 방법론
- 이론 계산 연구이므로 특별히 없음.

---

## 4. 연구 활용 포인트
- 파트 III의 적분 전개 방식을 내 코드의 slope integral 단순화에 적용할 수 있을까?
- 이 식은 가중함수를 파수($k_x$, $k_y$)에 대해 2차원 테일러 전개를 한 것이므로, 파수가 작을 때 (즉 파장이 길 때) 적용된다.
- Slope integral은 피적분함수를 표면 경사($S_x$, $S_y$)에 대해 2차원 테일러 전개를 해야 할 것이므로, SSA 가정 하에서 일단 가능해 보인다.
- 단, 피적분함수가 유전율(주파수, 온도, 염분) 및 스펙트럼(풍속, 풍향)의 함수로 나타날 것이므로, 구체적인 방식에 대한 고민이 필요하다.
  - 유전율, 스펙트럼에 의존하는 table 또는 딥러닝 모델 개발

---

## 5. 상세 내용
- PO 모델에서 포함하지 않는 효과로 (1) incidence shadowing, (2) Stogryn shadowing, (3) pdf scaling, (4) multiple scattering 등이 있다.

---

## 6. 같이보기
- 이 Wiki 내부의 주제
  - 내부 링크  

- 관련 논문
  - 선행, 후속, 유사 연구
