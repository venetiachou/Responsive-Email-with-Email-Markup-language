
## joinSuccessfully 

- 送信時機：消費者加入揪團後寄發信件
- 標題：揪團通知：你已成功加入{{groupName}}囉！
- 來自小夥伴的貼心小叮嚀：
1. logo 請放商家 logo & 連結到官網
2. 查看優惠進度請直接連到揪團網址
3. 距離 30% 優惠還差 50 件請幫我換上對的參數
4. 四個 icon 的分享我都沒有設定，但我相信懷恩老師知道我想幹嘛（扭）
5. companyName 放商家名稱，最底下的 `歡迎洽詢{{companyName}}` 的連結請放聯繫客服的連結
6. 有放 schema、有放 schema、有放 schema!!! 我直接放 JSON 一排在 body 最前面，大哥麻煩也對照參數，有些必要的 requirements 你可以看看 Google 的指南文件（附在最下面連結），如果你有困難的你就不要放
7. preheader 也有參數唷
8. 凡是 `#00b5ad` 這個色碼都是要換成品牌色系的
9. 團員明細那裡除了姓名、電話、Email 之外，我沒有補上地址還有客製欄位，但如果有就繼續照排在團員明細這個區塊裡 


## groupEnded

- 送信時機：揪團結束並成功扣款
- 標題：揪團通知：{{groupName}}已結束並成功扣款囉！
- 來自小夥伴的貼心小提醒：
1. 模板上的參數多數跟上ㄧ封一樣
2. 唯一需要您留心的是這封已有確切的訂單總金額， schema 上面也請放上最後的付款數字，以及 discount 的金額

## Special thanks
[Konstantin Savchenko](https://github.com/konsav/email-templates) 

[Gmail - Email Markup](https://developers.google.com/gmail/markup/getting-started)

[Gmail - Email Markup Tester](https://www.google.com/webmasters/markup-tester/)
