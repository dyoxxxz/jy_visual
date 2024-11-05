# 1. 고객 별 재구매 시기 데이터 분석 테블로 시각화 

![histogram](histogram.png)
# 고객 재구매 분석

이 그래프는 고객이 첫 번째 구매 후 두 번째 구매를 하기까지 걸린 일 수를 구간별로 나타낸 **히스토그램**입니다.

- **x축**: 첫 번째 구매 후 두 번째 구매까지 걸린 일수를 10일 단위로 구간화한 값입니다.  
  (예: 0-10일, 10-20일, 20-30일 등)
- **y축**: 해당 구간에 속하는 고객의 수를 나타냅니다.

### 그래프 해석

- 첫 번째 구매 후 두 번째 구매까지 걸린 시간이 **0-50일 사이**에 가장 많은 고객이 존재합니다.
- 특히 **30-40일 구간**에서 가장 많은 고객이 두 번째 구매를 한 것으로 보입니다.
- 시간이 지남에 따라 두 번째 구매를 하는 고객 수가 점차 줄어드는 경향을 보입니다.
  - 즉, 시간이 길어질수록 두 번째 구매를 하는 고객 수가 감소하는 패턴을 확인할 수 있습니다.

### 마케팅 전략

이 데이터를 바탕으로 다음과 같은 마케팅 전략을 고려할 수 있습니다:

1. **재구매 유도 프로모션**: 첫 구매 후 약 **30~40일 사이**에 재구매를 유도하는 프로모션을 진행하는 것이 효과적일 수 있습니다.
2. **고객 리텐션 강화**: 시간이 지남에 따라 재구매율이 떨어지므로, **50일 이후**에도 재구매를 유도할 수 있는 다양한 방법(예: 할인 쿠폰, 맞춤형 추천)을 적용할 필요가 있습니다.

### 결론

이 그래프는 고객의 재구매 패턴을 분석하고, 이를 바탕으로 적절한 마케팅 전략을 세우는 데 매우 유용한 정보를 제공합니다.

# 2. 고객 세그먼트 별 매출액 추이 그래프 

![매출액 그래프](이중축.png)

# 연도별 주문 금액 및 재구매 패턴 분석

## 연도별 주문 금액 변화

이 그래프는 2016년부터 2019년까지 세 가지 카테고리(또는 그룹)의 연도별 주문 금액 변화를 나타냅니다.

- **소비자**: 가장 높은 주문 금액을 기록한 그룹으로 매년 꾸준히 성장하고 있습니다. 
  - 2016년에 약 **305,647,413**, 2019년에 약 **623,515,110**을 기록했습니다.
  
- **기업 고객**: 중간 수준의 주문 금액을 기록하며 꾸준한 성장을 보였습니다.
  - 2016년에 약 **228,186,239**, 2019년에 약 **354,098,396**으로 증가했습니다.

- **홈 오피스**: 초기에는 낮은 수치였으나 빠르게 성장하여 2019년에 약 **258,862,485**를 기록했습니다.

# 3. 고객 새그먼트 별 매출액 누적 막대 그래프

![매출액 그래프](누적막대그래프.png)

# 연도별 매출 분석 (2016-2019)

이 그래프는 2016년부터 2019년까지 **소비자**, **기업 고객**, **홈오피스** 부문별 매출을 보여주는 누적 막대 그래프입니다. 각 색상은 다음과 같은 부문을 나타냅니다:

- **주황색:** 소비자
- **파란색:** 기업 고객
- **빨간색:** 홈오피스

### 연도별 매출 데이터

| 연도   | 총 매출         | 소비자 (주황색)   | 기업 고객 (파란색) | 홈오피스 (빨간색) |
|--------|-----------------|-------------------|--------------------|-------------------|
| **2016** | 651,935,270     | 305,647,413       | 228,186,239        | 118,101,618       |
| **2017** | 776,953,801     | 412,046,716       | 223,188,208        | 141,718,876       |
| **2018** | 991,771,824     | 511,557,409       | 294,562,798        | 185,651,617       |
| **2019** | 1,236,475,991   | 623,515,110       | 354,098,396        | 258,862,485       |

### 주요 포인트
1. **전체 매출**은 해마다 꾸준히 증가하고 있습니다.
2. 각 부문별로 살펴보면:
   - **소비자 부문**은 매년 큰 폭으로 성장하고 있으며 2019년에 가장 높은 매출을 기록했습니다.
   - **기업 고객 부문**은 꾸준히 성장하고 있지만 상대적으로 완만한 증가세를 보입니다.
   - **홈오피스 부문**은 가장 작은 비중을 차지하지만 매년 상승세를 보이고 있습니다.

### 시각적 설명
- **2016년**: 소비자 부문이 가장 큰 비중을 차지하며 홈오피스는 상대적으로 작은 비중을 차지함.
- **2017년**: 소비자 부문의 성장이 두드러지며 홈오피스 부문도 소폭 상승.
- **2018년**: 모든 부문에서 고른 성장이 이루어졌으며 특히 소비자와 기업 고객 부문의 성장이 눈에 띔.
- **2019년**: 소비자와 홈오피스의 급격한 성장이 눈에 띄며 전체 매출에서 큰 비중을 차지함.
