# Risk-management-LPPL-PPO2-trader

## 강화학습(PPO2 알고리즘)과 위험성회피 전략(LPPL모델, Turblence index)을 적용시킨 트레이더

다중공선성

약한 정상성 시계열데이터가 약한정상성을 만족하려면
시계열데이터가 평균,분산이 시간에 의존하지않고 공분산은 시간이 아닌 시차(t의 텀)에만 의존해야함
이로인해 생기는 정상 시계열 모형 = MA, AR모형

약한의존성t=> inf로 갈때 상관관계가 0으로 수렴한다면 약한의존성 만족


약한정상성과 약한 의존성을 가진다면 대수의법칙 적용가능

대수의 법칙은 ‘경험적 확률과 수학적 확률과의 관계를 나타내는 정리(定理)’이다. 즉, 표본의 관측대상의 수가 많으면 통계적 추정의 정밀도가 향상된다는 것을 수학적으로 증명한 것이다. 이론적으로는 다음과 같다.

‘무한 모집단에서 무작위로 추출된 확률변수 X가 독립적으로 동일한 분포에 따르고 E(X)=μ, V(X)=σ2인 경우, 표본의 크기가 커짐에 따라 표본 평균 =∑xi/n은 확률적으로 모집단의 실제 평균값 μ에 수속(收束)한다
[네이버 지식백과] 대수의 법칙 [law of large numbers, 大數法則] (21세기 정치학대사전, 정치학대사전편찬위원회)


