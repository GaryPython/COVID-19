China疫情統計
==========================
資料處理<br>         
--------------------------
*缺失職補齊<br>
*選定特定國家與日期<br>
*中文英文對照參數<br>


視覺化<br>
-----------------------------
目標:在中國地圖上呈現確診人數<br>
     
MAP_1<br>


>問題:資料呈現不直觀，太單調<br>
>解決方法:使用色階的方式來做出區別<br>

MAP_2<br>


>問題<br>
>>因為有離群職，導致最高的值與前75%差距過大，色階分布不均<br>
>解決方法<br>
>>把色階分層，且不設定最大值，讓離群值不干擾標準範圍內的數值<br>
>![Data_describe](https://github.com/GaryPython/COVID-19/blob/main/COVID-19%20China_visualization/Picture/data_describe.JPG)


MAP_3<br>
>優點:<br>
>>可清楚把感染人數分類，標示出危險區域<br>
>缺點:<br>
>>目前只能單一展現出一種情況，因再增加其他指標<br>
>>無時間線變化，只能觀察觀察同一時間點

[參考資料來源](https://kknews.cc/zh-tw/code/44vlokq.html"哈囉")


