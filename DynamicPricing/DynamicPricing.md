
# Dynamic Pricing

## 현재까지의 진행

지금의 Dynamic Pricing은 다음과 같은 정의를 가지고 있습니다.

- `Optimal Pricing`을 달성하기 위한 꾸준한 가격의 변경

  ![Image1](https://i2.wp.com/marketbusinessnews.com/wp-content/uploads/2017/10/Optimal-Price-image-with-definition-and-example.jpg?resize=500%2C363&ssl=1)

- 따라서 `Demand(수요)`에 대한 정의가 필요합니다.

  - `수요`에 대한 정의는 다음 링크를 통해 알 수 있습니다.
    [수요 - Wikipedia](https://ko.wikipedia.org/wiki/%EC%88%98%EC%9A%94)

- 따라서 `Dynamic Pricing`을 위해서는 다음과 같은 과정이 필요합니다.

```
1. Demand Function의 정의 (Y)
2. Revenue Function의 정의 (F(X))
3. Optimal Price의 정의 (X)
4. Optimal Price에 대한 평가 방법 (Validation)
```



## 현 상황

- 제한된 특정 상황에 대해서 `Dynamic Pricing` 적용하기
  - `서울에 한하여`와 같은 지역적인 제한
  - `쿠폰을 제외한`과 같은 변동 상황의 제한
  - `1일 이내`와 같은 시간적인 제한
- 예측 모델의 정확성을 올리는데 주력 (⭐️⭐️⭐️)
- 범위를 좁히더라도 이런 모델을 만들 수 있다 라는 것에 주력
- `Demand (수요)`를 정확하게 예측하는 모델을 제작하는 것을 목표로
- (전에 언급했던) Demand를 정확하게 예측하는 모델을 제작
  - Log-scale의 경우 곡선임에도 Linear한 모델이 될 수 있다
  - 수요 변화를 추측하고 싶음
  - 이러한 Linear 모델이 꽤 유용하게 쓸 수 있지 않을까 하는 기대가 있음
- 어떤것을 Optimize해야 하는지
  - 수요를 정확하게 예측하는 것을 목표로
  - 수요 x 가격 = 매출의 공식으로...
    (수요/가격 조합 중 매출이 가장 높은 것을 고르는 방식)
