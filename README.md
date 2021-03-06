# 簡易版登入器

使用Node.js, Express, Express-handlebars 套件製作而成

![Alt text](https://github.com/hsiyu1121/account_login/blob/master/Account%20Login.png)

## 功能清單
* 使用者可輸入帳號密碼並提交
* 帳密錯誤，使用者可以得到提示訊息，並且保留原本輸入帳號密碼
* 帳密正確，使用者將跳轉至歡迎畫面
* 點擊導航列可以回到首頁

## 環境需求
* Node.js: v10.15.0
* express: v4.17.1
* express-handlebars: v5.1.0
* body-parser: v1.19.0

## 啟動方式
* 將專案下載至本機內

  ``git clone https://github.com/hsiyu1121/account_login.git``
* 切換至資料夾內

  ``cd account_login``
* 安裝相關的套件

  ``npm install``
* 執行程式

  ``npm run start``
* 透過nodemon執行程式

  ``npm run dev``
* 開啟瀏覽器輸入以下網址

  ``http://localhost:3000``

## 測試帳號密碼清單
<table>
  <tr>
    <td></td>
    <td>Name</td>
    <td>Email</td>
    <td>Password</td>
  </tr>
  <tr>
    <td>1</td>
    <td>Tony</td>
    <td>tony@stark.com</td>
    <td>iamironman</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Steve</td>
    <td>captain@hotmail.com</td>
    <td>icandothisallday</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Peter</td>
    <td>peter@parker.com</td>
    <td>enajyram</td>
  </tr>
  <tr>
    <td>4</td>
    <td>Natasha</td>
    <td>natasha@gamil.com</td>
    <td>*parol#@$!</td>
  </tr>
  <tr>
    <td>5</td>
    <td>Nick</td>
    <td>nick@shield.com</td>
    <td>password</td>
  </tr>
</table>
