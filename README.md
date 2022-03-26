# TradingView_MLP_Neural_Indicator

Neural network indicator implemented based on MLP. MLP를 기반하여 구현된 신경망 인디케이터입니다.

Divergence for Many Indicators v4++ MLP neural network
https://kr.tradingview.com/script/I92RK8bB/

[Prophet 예측모델](/Prophet_Coin_Ai.ipynb)

앞으로 얼마나 변동성이 생길지를 다이버전스 발생 종류와 이전 가격의 고가, 저가 평균가를 입력 노드로 받아
학습한 뒤 예측결과를 차트에 표시해줍니다.

트레이딩뷰의 파인스크립트 특성상 2차원 배열이 없기 때문에
가상 2차원 배열을 1차원 배열로 구현해 행렬곱을 구현했습니다.
