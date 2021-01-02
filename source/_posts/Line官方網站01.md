---
title: google app script
date: 2020-12-22 20:22:46
---

#### 前言 

使用google app script 方式開發功能是非常方便的工具，但使用方式可能跟一般在運行javascript不太一樣，它是有一套自己運行週期，而主要程式語法還是圍繞在jacascriptgp身上，也有封裝包好google相關套件上，例如試算表等。

#### 製作 LINE 官方網站 訂單查詢





#### app script 相關窗口

1. onOpen(e) 當用戶打開用戶有權編輯的電子表格，文檔，演示文稿或表單時運行。

2. onInstall(e) 當用戶從Google文檔，表格，幻燈片或表單中安裝編輯器加載項時運行。

3. onEdit(e) 當用戶更改電子表格中的值時運行。

4. onSelectionChange(e) 當用戶更改電子表格中的選擇時運行。

5. doGet(e) 當用戶訪問網絡應用或程序將HTTP GET請求發送到網絡應用。

6. doPost(e) 當程序將HTTP POST請求發送到Web應用程序時運行。

上面各項函數是透過執行google app script主要執行窗口，想像是程式碼執行會先啟動位置。