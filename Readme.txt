架構應該是gameboard只負責遊戲行為(打開方塊 設標誌 判斷輸贏 生成版面)
然後用Controller的command_handler接收跟分析輸入格式
最後console遊戲介面跟GUI介面透過controller輸入
GUI的介面跟controller的介面到時候再對接 這樣
sound_effect目前還沒想法要怎麼做