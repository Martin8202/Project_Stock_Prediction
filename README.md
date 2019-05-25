<H1>Project：Stock Predtiction</H1>

使用**CAPM理論**與**統計信賴區間**概念，計算當日股價最高點與最低點，超過理論高點賣出，反之則買進。

<H2>File Description</H2>

* Data：<br>
    1.外部資料檔：氣溫、雨量、濕度、用餐時段、星期幾
    2.歷史資料檔：餐廳經緯度、愛評網評分、使用者評分、使用者過去用餐結果
* collect_code：<br>
    1.透過爬蟲或API蒐集外部資料之程式(R)
* Database：<br>
    1.使用RSQLite建立資料庫。
    2.後期開發以MongoDB為資料庫，附上讀取之程式碼。
* shiny：<br>
    1.以shiny呈現之程式檔(R)
* RandomForest.R：<br>
    1.以隨機森林模型建立推薦餐廳
    
<H2>Some Example</H2>

*   推薦系統Demo
![image](https://github.com/Martin8202/Project_Lunch_recommendation_system/blob/master/recommandation%20system_new.png)


 
