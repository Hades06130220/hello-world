名稱：以功能關閉
在：
  問題：
    類型：[帶標籤]

職位：
  建立：
    運行：ubuntu-latest
    步驟：
    -名稱：關閉問題
      用途：peter-evans / close-issue @ v1
      如果：contains（github.event.issue.labels。*。name，'feature'）
      與：
        評論：|
          謝謝您的要求。維護者將該請求分類為功能。
          
          我們認真對待所有對功能的要求，並將其傳遞給內部團隊供他們考慮。
          
          由於任何功能都需要該團隊長期維護和支持，因此我們在添加新功能時要謹慎行事。如果此功能可以獨立實現，請考慮分叉此存儲庫並添加功能。
