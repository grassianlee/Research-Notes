# A Study of Ocean-Like Surface Thermal Emission and Reflection Using Voronovich’s Small Slope Approximation

**Johnson (2005), IEEE TGRS**

**Created:** 2026-01-02 / **Updated:** 2026-01-02  
**Keywords:** Small slope approximation, thermal emission, reflection of downwelling brightness  

---

## 1. 개요
본 연구에서는 Voronovich의 "active" small slope approximation (SSA)을 기반으로 해수면과 유사한 표면의 방출을 몬테카를로 방법을 이용하여 계산했다. 이 결과는 two-scale 방법 및 passive SSA의 결과와 비교되었으며, 두 방법은 표면의 높이 규모가 작을 때는 대체로 일치했으나, 높이가 증가할 수록 일치도가 감소했다.  

---

## 2. 핵심 구조
- Active SSA 모형의 계산을 위해 주기성을 갖는 표면에서 몬테카를로 방법을 적용한다.
- 주기성을 갖는 표면을 정의한 후(식 1), 산란 전기장을 Floquet mode의 합으로 표현한다(식 6). 각 Floquet mode의 진폭은 SSA 급수로 표현 가능하며, 여기서는 첫 두 번째 항까지 나타냈다(식 17, 18). 이때 Floquet mode는 표면의 주기성에 의해 나타나는 이산적인 해를 말한다.
- 전자기파의 power는 전기장의 제곱으로 표현되며(식 28), 이를 전개하면 식 30과 같이 여러 차의 항을 얻을 수 있는데 몇 번째 항까지 포함하는지에 따라 SSA2, SSA3, SSA4를 정의할 수 있다.
- 키르히호프 법칙을 적용함으로써 표면 방출 밝기온도를 얻고(식 34-37), 상수 값인 표면온도를 대기 온도 프로파일로 대체함으로싸(식 44, 45) 하향복사의 반사 밝기온도를 얻는다.  

---

## 3. 방법론
- Section III는 생략함.

---

## 4. 연구 활용 포인트
- 대기 하향복사는 산란계수에 대한 직접적인 고려가 필수적인데, two-scale 방법에서 어떤 cutoff를 택하더라도 active SSA와 결과 차이가 상당히 있었다. Two-scale 모형으로 계산된 대기 하향복사를 어느 정도 믿을 수 있을지 고민이 필요하다.

---

## 5. 상세 내용
- 여기서 이산합은 주기성을 갖는 표면이기 때문에 사용된 것으로, 실제 랜덤 표면에서는 적분으로 나타날 것이다.
- 적어도 SSA3를 사용해야 밝기온도 모의가 제대로 가능한 것으로 보인다.
- 표면의 높이 규모가 클 때 SSA와 two-scale 방법의 모의 밝기온도 차이가 컸으며, 적절한 cutoff 파수를 찾는 것이 어렵다.

---

## 6. 같이보기
- 이 Wiki 내부의 주제
  - 내부 링크  

- 관련 논문
  - 선행, 후속, 유사 연구
