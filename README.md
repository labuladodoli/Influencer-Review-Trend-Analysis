網紅評價趨勢分析流程

1.使用selenium套件至Youtube抓取特定網紅最近30部影片下面包含該網紅名字與特定綽號的評論，並輸出成excel檔案。

2.將所有評論輸入進情緒分析模型(paddle paddle)，得到該評論是褒是貶或中性評論，若是褒則+1分，是貶則-1分，中性評論分數不變，以獲取隨留言數增加，網紅評價趨勢如何改變。



優點:構建一個半自動化的網紅評價分析模板(要手動設置網紅關鍵字)

缺點:依留言順序去增減網紅評價趨勢有其瑕疵，若改成個別針對30部影片做分析，然後依時間順序列出評價分數/評價數，應該能獲取更公正的趨勢圖。
