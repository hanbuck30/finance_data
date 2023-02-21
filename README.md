# finance_data
* It is about finance_data

* This model will stock data to predict future
* 전날 거래량과 나스닥 지수 ,s&p지수, 전날 환율이 다음날의 종가에 미치는 영향을 알아보고자 regression을 여러가지 model을 통해 predict를 잘하는 것을 알아볼 것이다
* model에는 linear model, descion tree계열, 그리고 esn을 사용할 계획이다
* finance_data_change는 전날과 종가의 차이를 비교 해줍니다
* reset_index()는 multi index를 없애주고 0부터 차례대로 정렬해주는 기능을 가지고 있고 차례대로 정렬을 위해 이를 사용하였다면 drop(columns=['index']를 해줘야 합니다 
