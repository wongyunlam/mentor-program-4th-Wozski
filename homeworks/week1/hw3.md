## 教你朋友 CLI

Commamd Line是內建的系統，可以使用指令來對電腦下指令，我們平常使用的建立新檔案或是資料夾，一般使用滑鼠右鍵建立新檔案或是資料夾是所謂的 GUI ,意思是圖像介面系統，而使用 CLI 就是使用指令來做這些事，到這裡也許你就會問，能夠使用滑鼠右鍵就能完成的事情，為什麼需要用到指令，這樣不是自找麻煩嗎?
但是電腦有一些功能是沒有 GUI 的介面，或者使用 GUI 太消耗電腦資源，相對的使用指令可以大大減少電腦的負擔
接下來的問題是如何建立一個資料夾並且在裡面新增一個 afu.js 的檔案。

### 裡面$的符號代表在 CLI 環境下輸入的指令，指令輸入完後按下 Enter 完成指令輸入。

1. 如果環境是 Windows 打開 Cmd ，如果是 MAC 系統則是使用 Terminal(終端機）
2. 使用 $CD 這個指令前往桌面(Desktop),這樣方便你稍後找到檔案
3. 到了桌面後 CLI 會顯示 以下以我電腦為例子： C:\Users\work\Desktop\ 正常情況下會顯示這樣的資訊，之後輸入 $mkdir + wifi(代稱新的資料夾名稱)，即可成功創建資料夾，完成後一樣使用 $ cd wifi 進入資料夾內。
4. 進入資料夾後會顯示 C:\Users\work\Desktop\wifi，代表你成功進入資料夾內，接著使用 
$echo (你要輸入的內容，可寫可不寫)> afu.js(你要命名的檔案名稱)，在成功輸入後，就可以去資料夾內看是否檔案已經成功被建立。

### 補充資料 
$ cd(Change Directory)-切換資料夾 (cd … or cd ~ 可以回到上一層) (cd + tab-可以讓電腦幫你輸入，只需要輸入關鍵字)
$ mkdir(MaKe DIRectory)-建立資料夾
$ echo-將資訊輸出到檔案中