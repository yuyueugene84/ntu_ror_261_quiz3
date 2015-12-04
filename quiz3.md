1. 請解釋 database.yml, routes.rb, 和 gemifle 分別是什麼？ 他們分別在一個 Rails 專案裡的什麼位置？ 他們為什麼對一個 Rails 專案如此重要？

2. MVC 架構裡的 M, V, 和 C 分別代表什麼？ 

3. 請解釋 CRUD 是哪四個字的縮寫？  

4. 請問在 routes.rb 裡面加入以下程式碼會產生出哪一些 url？ (提示：在 browser 輸入```http://localhost:3000/rails/info/routes```)
	```ruby
	resources :users
	```
5. 請解釋 model 檔案和 migration 檔案的差別

6. 若今天發現一個 migration 檔寫錯，請問我應該用什麼指令回復到上一個版本的 migration? 

7. 請解釋什麼是 ActiveRecord? 

8. 假設今天
	* 我要在資料庫裡產出一個叫 group 的資料表
	* 裡面包括的欄位名稱和相對應的資料型別是： 
		name (string),
		description (text),
		members (integer)
請寫出一個能產生出以上需求的 migration 檔
