# pixnet_crawler

## 目標

* https://www.pixnet.net/blog

* 收集當日最熱門的貼文，累積痞客邦論壇數據

* 痞客邦不如其他論壇，無法取得過往資料，假設有已知且想追蹤的作者，能透過另一種方式(作者 uid+ get_article_url_by_author function)，
抓取該作者所有公開貼文

* 其中內文標籤可作為，自訂標籤依據，亦能成為有用字典

### 注意

* 需要更改下載圖片的存放路徑以及mysql設定檔，可參考additional_file中的sql_config.txt範例檔

* 下載的圖片檔可參考 <~順順的美麗日記~-628985d3de71145627> ，資料夾命名規則為 <author_name>-<article_id>

### 數據示意

* 表格

board: 每日熱文文章收集

authorboard: 抓取該特定作者貼文

![](https://i.imgur.com/EYtw8jy.png)

* 文章數據

![](https://i.imgur.com/BtdTswe.png)

* 留言數據

![](https://i.imgur.com/Zhd9f8B.png)
