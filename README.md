
## 請完成以下事項



### 當使用者重新整理頁面時，資料能重現

###### 1-1.實作`function validate (inputValue) -> Boolean`
當 inputValue 長度大於 3 的時候回傳 true(有效) 否則 false

###### 1-2.運用 validate 檢查 todoInputEle 的 value 是否有效
若有效則執行 `validateHintEle.className = "has-success"` 否則 `validateHintEle.className = "has-error"`

___

### 當使用點選新增按鈕時，儲存資料並顯示
### 當使用者點選在 todo element上面時，新增 class list-group-item-success

###### 2-1.將新增的 TODO 用 object 表示（以下指稱`todoData`)，並存進陣列`todoDataArray`裡面
。需有[敘述文字]以及[完成與否]兩屬性(物件的 key 請自己命名)。

###### 2-2.點選新增按鈕時：2. 用上一步驟的 object 裡的資料 創建 todo 的 `Element`
* 結構：`<a href="#" class="list-group-item">TODO的敘述文字</a>`
* 此 element 監聽 click 事件，觸發時：
	將對應的 `todoData` [完成與否] 值設定為完成狀態(true)
	呼叫 `updatetodoListEle(todoDataList)`
###### 2-3.將創建的 todoElement 顯示在 `todoListEle` 裡。
###### 2-4.將`todoDataList`存進 `localStorage`

___

### 當使用者輸入時，長度不為 3 會提示錯誤訊息

###### 3-1.將步驟 2-2 變成一個 `function createElement (todoData) -> Element`
###### 3-2.實作 `function updatetodoListEle (todoDataList) -> undefined` 的方程式
* 清空 todoListEle 內的所有子元素
* 運用`createElement` 創建 todoDataList 裡的每一筆 todoData 的 `Element`

###### 3-3. 讀取 localStorage 裡的資料，並重新顯示。



###### ref : HTMLInputElement
###### ref : Element
