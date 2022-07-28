# ELK Dashboard 實作練習 - 以銷售資料為例

### 目標

以 Logstash 設定日期與經緯度資料型態，並 output 至 Elasticsearch 再以 Kibana 進行分析。

### 分析檔案

資料
[Sales.csv](https://github.com/StevenHsu22/ELK_dashboard/blob/main/sales.csv)

Config 檔
[log_config](https://github.com/StevenHsu22/ELK_dashboard/blob/main/log_config)

### 呈現結果

Dashboard 呈現共 7 大圖表，年度銷售總表、前十大熱銷品牌、熱銷款式圓餅圖、季節服飾熱銷比率圓餅圖、成本分析折線圖、國內外生產與採購比率圓餅圖、前十名分店銷售額&毛利率長條圖。

![](https://github.com/StevenHsu22/ELK_dashboard/blob/main/dashboard_presentation.png)
