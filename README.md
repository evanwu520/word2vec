# word2vec
# 實作流程
1. 在 terminal 進行套件安裝以及下載資料格式檔案轉換 (若已有現成文本可略過) 
2. 在 jupyter notebook 透過 jieba套件斷詞，再經由 word2vec 萃取文章特徵，轉換成以向量空間表示的詞向量
3. 視覺化呈現相近詞向量之結果
---

## 本次使用資料集
==搜狗實驗室的新聞文本==(完整版648MB、tar.gz格式)；當然你也可以使用迷你版(110KB)，但要記得下載tar.gz格式的資料集，因示範程式碼是以此格式做清理。[下載連結](http://www.sogou.com/labs/resource/cs.php)


## 會使用到的套件
- jieba
- sklearn
- matplotlib
- numpy
- 須下載可呈現中文字的[支援文件](https://github.com/sebastianbergmann/phpunit-documentation/blob/master/build/fonts/wqy-microhei/wqy-microhei.ttc)
