# Onion_Rime_Files（電腦 Rime 注音、雙拼、拼音、行列30 洋蔥 方案）

####  ※ 請勿使用於商業營利相關行為
####  ※ Commercial use is prohibited

### 內容說明：
- allfiles 中包含九個主方案（三個注音、一個注音雙拼、一個拼音、三個形碼、一個行列30）和一眾掛接方案

- 三個形碼方案無法使用，因已刪除碼表內容！

- allfiles 中的檔案不以一個資料夾一個方案，為了較好更新（不用同一個檔案更新數次）

- 提供 Python (sort_rime_file.py) 文件，把 Rime 文件分門別類到各個方案資料夾，使其易安裝部署

### sort_rime_file.py 使用方法：
- 於本倉庫 Onion_Rime_Files 中按右上綠色 〔↓Code〕 ⇨ Download ZIP ⇨ 解壓縮 ZIP ⇨ 進入解壓縮後的資料夾，確認 allfiles 資料夾 和 sort_rime_file.py 是在同一層 ⇨ 執行 sort_rime_file.py ⇨ 產生一個『電腦RIME方案_{當天日期}』資料夾

- 產生的『電腦RIME方案_{當天日期}』該資料夾內，會把各方案所須使用的文件，分別安放在該『方案名稱』資料夾，安裝部署時，把內含文件通通放入『 Rime 』安裝資料夾中（預設已有 opencc 資料夾，移動方案 opencc 裡面檔案到電腦 rime/opencc ），按「重新部署」即可使用。

  > 《 Windows 用戶注意！！！》，注音洋蔥 plus 版和注音洋蔥 mix‧in 版掛接《Easy》，使用提示碼做英漢字典，但 Windows 輸入時，整頁提示碼太多會使程式崩潰！故以正則簡化提示碼！不過 Windows 可行程式碼在 Mac 會使《Easy》無法正常出字！提供 custom 檔給 Windows 用戶，防止程式崩潰（ Mac 用戶勿使用該 custom 檔）。分別在「plus注音_防崩潰：Win必加，Mac勿加」和「mixin注音_同顯2修改檔(Win)」資料夾內，Windows 用戶把資料夾內 custom.yaml 檔拖到上一層（和方案中其他文件同一層），按「重新部署」即可。

  > 如果缺少檔案，會立即出錯無法執行！
  
  > 用 Visual Studio Code 等非 Python 原生程式執行 sort_rime_file.py 會出錯（需另設定），使用 Python 原生程式執行即可。

### 各方案說明：

> 目前關閉，各方案說明等有閒情逸致時再移植來 GitHub 這邊。

- [電腦 RIME 輸入法『注音 洋蔥純注音版』](https://deltazone.pixnet.net/blog/post/264319309)

- [電腦 RIME 輸入法『注音 洋蔥plus版 』](https://deltazone.pixnet.net/blog/post/343650692)

- [電腦 RIME 輸入法『注音 洋蔥mix‧in版 』](https://deltazone.pixnet.net/blog/post/347368709)

- [電腦 RIME 輸入法『注音 洋蔥雙拼版 』](https://deltazone.pixnet.net/blog/post/359775341)

- [電腦 RIME 輸入法〖 地球拼音 洋蔥mix‧in多國語言-擴充版 〗](https://deltazone.pixnet.net/blog/post/353697089)

- [電腦 RIME 設定檔〖 洋蔥版 行列30 〗](https://deltazone.pixnet.net/blog/post/361766142)


### Demo：

- 注音 洋蔥 mix-in 版
  
  > 集大成，多國語言和注音混打輸入 😃！
  
  #### ![image](https://github.com/oniondelta/Onion_Rime_Files/blob/master/demo_mixin.gif)
  
- 注音 洋蔥 plus 版

  > 功能多，除外語還有一堆功能和細節增加，輸入手感和純注音版一樣，即使沒用外語，也推薦使用！
  
  #### ![image](https://github.com/oniondelta/Onion_Rime_Files/blob/master/demo_plus.gif)
  
- 注音 洋蔥 純注音 版
  
  > 功能少，給新手使用，較不推薦！
  
  #### ![image](https://github.com/oniondelta/Onion_Rime_Files/blob/master/demo_pure.gif)
  
### 贊助 Donate：

  > 從第一個方案上傳已持續更新四年！方案從頭到尾大改、新創、新增非常多功能！且做了許多圖文說明！花了族繁不及備載的心力！

  > 懇請贊助 (Donate) 支持，讓 Rime 洋蔥的一系列方案更新更有動力！

- [按此以〈綠界〉贊助 Donate：](https://p.ecpay.com.tw/D555162)

  #### [![donate1](https://payment.ecpay.com.tw/Upload/QRCode/202010/QRCode_170c287e-2db8-4b50-b87f-8d36500a3958.png)](https://p.ecpay.com.tw/D555162)

- [按此以〈歐付寶〉贊助 Donate：](https://qr.opay.tw/q1ql7)

  #### [![donate2](https://payment.opay.tw/Upload/Broadcaster/2294343/QRcode/QRCode_7AC0FA1CAD39F0B66CFD5513A2173D1A.png)](https://qr.opay.tw/q1ql7)

