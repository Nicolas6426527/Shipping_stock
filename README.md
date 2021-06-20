# Shipping_stock 台灣航運股分析
## 抓取時間： 2017/01/01～現在
### 抓取資料 >> 臺灣證券交易所、Goodinfo!台灣股市資訊網
1. 股價（最高價、最低價、收盤價）
2. 交易筆數
3. EPS
4. 本益比(PER)
5. 股價淨值比(PBR)
6. ROE\ROA

### 處理方式
1. 以每月的方式做處理（中位數） >> 股價、交易筆數、EPS、股價淨值比(PBR)  
2. 以每季的方式做處理 >> ROE\ROA


### 使用套件
- requests
- pandas
- numpy
- time
- BeautifulSoup
- datetime
- os
- seaborn
- matplotlib

