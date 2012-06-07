Version : LabVIEW 11.0f1 (32-bit) 
Auther  : Ares

2011/11/13  門禁初步架構完成
2011/11/14  修改Door Tread架構
2011/11/16  新增查詢同一卡號,錯誤n次後出現警示
2011/11/17  新增按鍵密碼確認開啟 
2011/11/18  新增LogFile for Server功能(預留)
2011/11/30  完成TCP Multi-Connection 與 TCP/UDP Client程式
2011/12/01  DoorAccess修正與TCP Server斷線重連的機制
2011/12/09  完成修改後的新架構
2011/12/13  修正Alerts Queue，Queue有可能會塞滿而停駐的問題
2012/01/18  加入Save VI Front Panel as default
2012/01/30  修改UI介面 & 加入TAB Control
2012/02/01  使用INI檔來儲存Front Panel的數值當成預設
2012/02/02  修正TCP斷線後的立即偵測可以即時顯示是否斷線
            使用Call Setup呼叫DoorTread.vi與立即啟動與關閉TCP

2012/03/02  新增LUT查詢機制，新增移除卡片判斷
            新增晚間N點以後，需要刷卡+密碼功能
            直接按鍵輸入4碼，密碼查詢功能







