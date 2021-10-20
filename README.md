# Revolution3

## **#1. 포트폴리오 수익률 (미국)**

<pre>- date :<i>str</i> 날짜
- amzn : <i>float</i> 아마존 주식 종가
- dpz :<i>float</i> 도미노피자 종가
- btc :<i>float</i> 비트코인 종가
- nflx :<i>float</i> 넷플릭스 종가
</pre>

#### **데이터 불러오기**
<pre><code>portfolio_data = pd.read_csv('https://raw.githubusercontent.com/fintech-data/Revolution3/main/data/portfolio_data.csv')
</code></pre>

## **#2 국제 포트폴리오 (한국, 미국)**

<pre>- DOW :<i>float</i> 다우존스 종가
- VIX	:<i>float</i> VIX지수 종가
- BTC	:<i>float</i> 비트코인 종가(24시 기준)
- ETH	:<i>float</i> 이더리움 종가(24시 기준)
- kospi :<i>float</i> 코스피 지수 종가
- vkospi :<i>float</i> 한국 변동성 지수 종가
- gold	 :<i>float</i> 금선물 지수 종가(한국)
- dol :<i>float</i> 달러 선물 지수 종가(한국)
- DOW1~ dol1 :<i>float</i>  각 지수의 종가 수익률(일일 수익률,  직전 거래일 대비%)
- corona :<i>str</i>  코로나 시기 여부 (2020.01.31 기준 WHO 펜데믹 선언 이전은 0 이후는1)</pre>

#### **데이터 불러오기**
<pre><code>international_portfolio_data = pd.read_csv('https://raw.githubusercontent.com/fintech-data/Revolution3/main/data/international_portfolio_data.csv')
</code></pre>
