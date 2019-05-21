## 통계 및 수학 질문공부 (성윤님 깃헙펌)
- 고유값(eigen value)와 고유벡터(eigen vector)에 대해 설명해주세요. 그리고 왜 중요할까요?
    ##### -행렬A 곱하기 x = L(람다,스칼라값) 곱하기 x
    
- 샘플링(Sampling)과 리샘플링(Resampling)에 대해 설명해주세요. 리샘플링은 무슨 장점이 있을까요?
    ##### -Resampling : Non-parametric Stat에서 사용하는 샘플링. 모수에대한 자료가 부족하거나 설명되기 힘든상황에서 사용되는 샘플링..

- 확률 모형과 확률 변수는 무엇일까요?
    ##### -확률변수는 P(X=3) 이라는 확률모형에서 X=3 부분임. 동전던지기를 예시로 생각해보면, Head or Tail이 나옴. 
    ##### -Head가 나올 확률을 Sample Space S = {H, T}로 표시할 수 있으며, P(X=H) = 1/2 헤드가 나온다는 자체를 확률변수로 대입.
    ##### -그 확률의 분포가 1/2, P(X=T) = 1/2 . 즉 1/2가 두번있는 확률분포를 알 수 있음. 동전던지기는 한 사건이 다음사건 영향 x. 이산적임(Discrete)

- 누적 분포 함수와 확률 밀도 함수는 무엇일까요? 수식과 함께 표현해주세요

- 베르누이 분포 / 이항 분포 / 카테고리 분포 / 다항 분포 / 가우시안 정규 분포 / t 분포 / 카이제곱 분포 / F 분포 / 베타 분포 / 감마 분포 / 디리클레 분포에 대해 설명해주세요. 혹시 연관된 분포가 있다면 연관 관계를 설명해주세요
    ##### -베르누이 분포와 이항 분포는 같은말(동전던지기, 앞뒷면이 나오는 확률분포는 베르누이 분포를 따름. Success or Fail)

- 조건부 확률은 무엇일까요?
    ##### - Conditional Probability (A|X)는 X가 주어졌을때 Event A가 일어날 확률을 의미..
- 공분산과 상관계수는 무엇일까요? 수식과 함께 표현해주세요
    ##### - 두 변수의 편차끼리 곱함 그리고 이를 평균내면 공분산. 해당 공분산 값을 두 변수의 표준편차로 나누어주면 상관계수임.
- 신뢰 구간의 정의는 무엇인가요?
    ##### - 구간추정시 평균값(Point)이 해당 분포에 포함되있을 가능성..이 95%, 97.5% 등등
- p-value를 고객에게는 뭐라고 설명하는게 이해하기 편할까요?
- p-value는 요즘 시대에도 여전히 유효할까요? 언제 p-value가 실제를 호도하는 경향이 있을까요?
- A/B Test 등 현상 분석 및 실험 설계 상 통계적으로 유의미함의 여부를 결정하기 위한 방법에는 어떤 것이 있을까요?

- R square의 의미는 무엇인가요? 
    ##### - R^2 회기식에서 설명력을 의미. 높을수록 설명력이 높다, 그러나 Feature 수가 많아지면 설명력은 무조건 올라가는 함정이..

- 평균(mean)과 중앙값(median)중에 어떤 케이스에서 뭐를 써야할까요?

- 중심극한정리는 왜 유용한걸까요?
    ##### - Central Limit Theorm은 Sample 수가 크게 증가할수록 가우시안 정규분포로 수렴한다는 가정성립.
- 엔트로피(entropy)에 대해 설명해주세요. 가능하면 Information Gain도요.
    ##### -Gini Impurity 가 낮아지는 방향으로 .. 디시젼트리
- 요즘같은 빅데이터(?)시대에는 정규성 테스트가 의미 없다는 주장이 있습니다. 맞을까요?
    ##### 터무니없는 주장임.. 정규성을 갖추어야 통계적으로 가장 fundamental한 분석 시작 가능
- 어떨 때 모수적 방법론을 쓸 수 있고, 어떨 때 비모수적 방법론을 쓸 수 있나요?
    ##### 모수적통계
- “likelihood”와 “probability”의 차이는 무엇일까요?

- 통계에서 사용되는 bootstrap의 의미는 무엇인가요.

- 모수가 매우 적은 (수십개 이하) 케이스의 경우 어떤 방식으로 예측 모델을 수립할 수 있을까요?
    ##### 오버샘플링? 아니면 비모수적 통계기법.. 리샘플링을적용한다?
- 베이지안과 프리퀀티스트간의 입장차이를 설명해주실 수 있나요?

- 검정력(statistical power)은 무엇일까요?

- missing value가 있을 경우 채워야 할까요? 그 이유는 무엇인가요?
    ##### missing value가 맞는지확인 후 맞다면 채워넣음. 평균, 최빈값, 중위값 등을 넣기도하며, 데이터를 drop해버리는 건 안좋은 초이스..
- 아웃라이어의 판단하는 기준은 무엇인가요?
    ##### 3 표준편차 from mean 값. Boxplot max, min 을 벗어나는경우 일반적으로..
- 콜센터 통화 지속 시간에 대한 데이터가 존재합니다. 이 데이터를 코드화하고 분석하는 방법에 대한 계획을 세워주세요. 이 기간의 분포가 어떻게 보일지에 대한 시나리오를 설명해주세요
- 출장을 위해 비행기를 타려고 합니다. 당신은 우산을 가져가야 하는지 알고 싶어 출장지에 사는 친구 3명에게 무작위로 전화를 하고 비가 오는 경우를 독립적으로 질문해주세요. 각 친구는 2/3로 진실을 말하고 1/3으로 거짓을 말합니다. 3명의 친구가 모두 "그렇습니다. 비가 내리고 있습니다"라고 말했습니다. 실제로 비가 내릴 확률은 얼마입니까?
- 필요한 표본의 크기를 어떻게 계산합니까?

- Bias를 통제하는 방법은 무엇입니까?
    ##### Variance를 높이는쪽으로..?
- 로그 함수는 어떤 경우 유용합니까? 사례를 들어 설명해주세요
    ##### log가 유용할때는 분포가왼쪽으로 치우쳐져있을때 로그를취하면 대략적인 정규분포가 이루어지며, NLP에서 TF-IDF계산시 log를 취하는데 이는 스케일을 작게만들기위함임
